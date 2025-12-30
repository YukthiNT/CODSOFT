# Task 2: Credit Card Fraud Detection

## Description
This project focuses on detecting fraudulent credit card transactions using machine learning.
Due to the highly imbalanced nature of fraud data, special techniques are used to improve fraud detection performance.

The model analyzes transaction details such as amount, merchant, location, time, and customer information to predict whether a transaction is fraudulent or legitimate.

## Dataset
The dataset is sourced from Kaggle:
Fraud Detection Dataset by kartik2112

It consists of two files:
- fraudTrain.csv
- fraudTest.csv

The dataset contains transaction details along with a target column is_fraud.

## Technologies Used
- Python
- Google Colab
- Pandas, NumPy
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Matplotlib
- Joblib

## Methodology
1. Loaded training and testing datasets
2. Removed identifier columns
3. Performed date-time feature engineering (hour, day, month, weekday)
4. Applied data preprocessing using:
   - RobustScaler for numerical features
   - OneHotEncoder for categorical features
5. Handled class imbalance using SMOTE
6. Trained multiple machine learning models:
   - Logistic Regression
   - Decision Tree
   - Random Forest
7. Evaluated models using:
   - Confusion Matrix
   - Classification Report
   - ROC-AUC
   - Precision-Recall AUC
8. Selected the best model based on PR-AUC score
9. Saved the best-performing model using Joblib
10. Tested the model on sample transactions

## Model Evaluation
The Random Forest model performed best with the highest Precision-Recall AUC score.
It effectively detects fraudulent transactions while handling class imbalance.

## Output
- ROC Curve and Precision-Recall Curve for the best model
- Fraud probability predictions for sample transactions
- Saved trained model file: best_fraud_model.joblib

## Author
Yukthi N T
