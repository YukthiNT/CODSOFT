# Task 3: Customer Churn Prediction

## Problem Statement
Develop a machine learning model to predict customer churn for a subscription-based service or business.
The model uses historical customer data, including usage behavior and customer demographic features, to predict whether a customer is likely to discontinue the service.

## Description
Customer churn prediction is an important business problem that helps organizations retain customers and reduce revenue loss.
This project analyzes customer information such as demographics, account details, and service usage to identify customers who are at risk of churn.

A Random Forest classifier is used to build the prediction model due to its robustness and ability to handle non-linear relationships.

## Dataset
The dataset is sourced from Kaggle and contains historical customer data for a subscription-based service.

File used:
- Churn_Modelling.csv

Target variable:
- Exited  
  - 1 → Customer churned  
  - 0 → Customer retained

## Technologies Used
- Python
- Google Colab
- Pandas, NumPy
- Scikit-learn
- Random Forest Classifier

## Approach
1. Loaded historical customer churn dataset
2. Removed irrelevant identifier columns
3. Encoded categorical features using one-hot encoding
4. Split data into training and testing sets with stratification
5. Scaled numerical features using StandardScaler
6. Trained a Random Forest classifier with class balancing
7. Evaluated the model using accuracy and ROC-AUC score

## Model Performance
- Accuracy: ~86%
- ROC-AUC Score: ~0.85

The model demonstrates good predictive performance in identifying customers likely to churn.

## Outcome
The trained model can be used by businesses to:
- Identify high-risk customers
- Take proactive retention measures
- Improve customer satisfaction and reduce churn

## Author
Yukthi N T
