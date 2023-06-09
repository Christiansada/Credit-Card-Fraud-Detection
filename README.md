# Credit Card Fraud Detection using Machine Learning Techniques

![image](https://github.com/Christiansada/Credit-Card-Fraud-Detection/assets/95037926/a2e61d4d-78c9-4dea-87d6-b1ffbf974884)

### Project Overview

This project involves the development of a predictive model to identify fraudulent transactions in credit card data.The main aim is to minimize the instances where customers are falsely charged for items they didn't purchase. We use traditional Machine Learning techniques.

### Dataset Description 
The dataset contains credit card transactions made by European cardholders in September 2013. The dataset is highly unbalanced with only 0.172% (492 out of 284,807) of the transactions being fraudulent. The features in the dataset are mostly numerical and are results of a PCA transformation due to confidentiality requirements, with features V1 to V28 representing the principal components. The exceptions to this are 'Time' and 'Amount' which represent the seconds elapsed between each transaction and the first transaction in the dataset, and the transaction amount respectively. The response variable 'Class' is binary, with '1' indicating a fraudulent transaction and '0' otherwise.

Due to the highly unbalanced nature of the data, we recommend the use of Area Under the Precision-Recall Curve (AUPRC) instead of the traditional confusion matrix accuracy for evaluating model performance.

### Project Pipeline

In this project, we will execute the following tasks:

1. Data Analysis: The initial step involves exploring the dataset to understand its structure, distribution and relationship between various features.

2. Feature Engineering: We will process and engineer features to make them suitable for use in our machine learning models.

3. Model Building and Prediction using ML Techniques: Traditional machine learning models will be trained and evaluated using the processed dataset.

Please check out the Jupyter notebook for a detailed walkthrough of the project.
