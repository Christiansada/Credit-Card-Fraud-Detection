# Credit Card Fraud Detection using Machine Learning and AutoML Techniques

!xenonstack-credit-card-fraud-detection.png

### Project Overview

This project involves the development of a predictive model to identify fraudulent transactions in credit card data.The main aim is to minimize the instances where customers are falsely charged for items they didn't purchase. We use both traditional Machine Learning techniques and Automated Machine Learning (AutoML) using PyCaret for this project. We also emphasize the use of Anomaly Detection to identify instances of fraud.

### Dataset Description 
The dataset contains credit card transactions made by European cardholders in September 2013. The dataset is highly unbalanced with only 0.172% (492 out of 284,807) of the transactions being fraudulent. The features in the dataset are mostly numerical and are results of a PCA transformation due to confidentiality requirements, with features V1 to V28 representing the principal components. The exceptions to this are 'Time' and 'Amount' which represent the seconds elapsed between each transaction and the first transaction in the dataset, and the transaction amount respectively. The response variable 'Class' is binary, with '1' indicating a fraudulent transaction and '0' otherwise.

Due to the highly unbalanced nature of the data, we recommend the use of Area Under the Precision-Recall Curve (AUPRC) instead of the traditional confusion matrix accuracy for evaluating model performance.

### Project Pipeline

In this project, we will execute the following tasks:

1. Data Analysis: The initial step involves exploring the dataset to understand its structure, distribution and relationship between various features.

2. Feature Engineering: We will process and engineer features to make them suitable for use in our machine learning models.

3. Model Building and Prediction using ML Techniques: Traditional machine learning models will be trained and evaluated using the processed dataset.

4. Model Building and Prediction using PyCaret (AutoML): We will use PyCaret, an AutoML tool, to automate the process of model selection, hyperparameter tuning and evaluation.

Please check out the Jupyter notebook for a detailed walkthrough of the project.
