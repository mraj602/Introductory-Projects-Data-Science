# Fraud Detection
### Project Overview
* Build a model to detect fraudulant transactions from an extremely imbalanced financial dataset.
* Cleaned, explored and manipulated the entire data extensively on Python to make it usable for our use case.
* Investigated the data and engineered new features as and when necessary in accordance with our project requirements.
* Applied Synthetic Minority Over-sampling Technique (SMOTE) and other measures to overcome extreme imbalance before modelling the classifier
### Project Introduction
In this project, I will be trying to detect fraudulant transactions from a financial dataset containing over 6 million records of transactions. The dataset is extremely imbalanced with minority (fraud) proportion. I will be trying to implement various measures to tackle the challenges and arrive at an acceptable fraud detection performance.
### Dataset
The dataset for this project can be found [here](https://www.kaggle.com/datasets/rupakroy/online-payments-fraud-detection-dataset)
### Features reference:

* step: represents a unit of time where 1 step equals 1 hour

* type: type of online transaction

* amount: the amount of the transaction

* nameOrig: customer starting the transaction

* oldbalanceOrg: balance before the transaction

* newbalanceOrig: balance after the transaction

* nameDest: recipient of the transaction

* oldbalanceDest: initial balance of recipient before the transaction

* newbalanceDest: the new balance of recipient after the transaction

* isFraud: fraud transaction
