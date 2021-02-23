# Melbourne Housing - Regression
The project focuses on whole workflow of a data scientist after collecting a data. This project mainly includes 4 types of Regression Model and tries the
best to answer the difference between all 4 models along with finding the best suitable model for our data.

# Libraries used
I have used Matplotlib and Seaborn for visualizing the data. Data Visualization is one of the important part of this project.

Further I have used numpy and pandas to manupulate data and then Sklearn to import various ML models.

# The Data
The data is contained in a CSV files. The data is about housing price in Melbourne with 21 different columns initially with the following row meanings:
Rooms: Number of rooms

Price: Price in dollars

Method: S - property sold; SP - property sold prior; PI - property passed in; PN - sold prior not disclosed; SN - sold not disclosed; NB - no bid; VB - vendor bid; W - withdrawn prior to auction; SA - sold after auction; SS - sold after auction price not disclosed. N/A - price or highest bid not available.

Type: br - bedroom(s); h - house,cottage,villa, semi,terrace; u - unit, duplex; t - townhouse; dev site - development site; o res - other residential.

SellerG: Real Estate Agent

Date: Date sold

Distance: Distance from CBD

Regionname: General Region (West, North West, North, North east …etc)

Propertycount: Number of properties that exist in the suburb.

Bedroom2 : Scraped # of Bedrooms (from different source)

Bathroom: Number of Bathrooms

Car: Number of carspots

Landsize: Land Size

BuildingArea: Building Size

CouncilArea: Governing council for the area

**The other variables have common meanings**

# Objective of Project
The main objective of the project is to build and train a model with as many features as possible to predict the price of a house in Melbourne. Our main question for analysis is:
 "How much is the price of house dependent on each feature and to predict the price of house for unknown value of those features"


# Workflow of Project
* Loading the data
* Exploring the data with dtype, isna(), describe() etc
* Handling the missing values (includes calculating the missing value using given data)
* Visualizing the features of data
* Finding the outliers and removing them
* Handling highly skewed data
* Preparing the data (includes LabelEncoding of categorical data and normalizing the data)
* Using multiple Regression Models (Multiple Regn, Polynomial Regn, Ridge Regn, Lasso Regn)
* Evaluating the models and choosing the best model for our data using finding reasons (Includes vizualization to find the coverage of our model)
* Predicting the price of house using 10 random generated values for our model

Feel free to give suggestions!
