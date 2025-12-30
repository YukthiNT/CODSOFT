# Task 4: Spam SMS Detection

## Problem Statement
Build an AI model that can classify SMS messages as spam or legitimate (ham).
The model uses text processing techniques such as TF-IDF along with machine learning classifiers to accurately identify spam messages.

## Description
Spam SMS detection is an important application of Natural Language Processing (NLP).
This project focuses on automatically detecting spam messages using historical SMS data.

TF-IDF is used to convert text messages into numerical features, and a Multinomial Naive Bayes classifier is trained to distinguish between spam and legitimate messages.

## Dataset
The dataset is sourced from Kaggle:
SMS Spam Collection Dataset (UCI ML Repository)

File used:
- spam.csv

Target labels:
- 1 → Spam
- 0 → Ham (Legitimate)

## Technologies Used
- Python
- Google Colab
- Pandas
- Scikit-learn
- TF-IDF Vectorizer
- Multinomial Naive Bayes

## Methodology
1. Loaded the SMS spam dataset
2. Cleaned and selected relevant columns
3. Converted text labels into numerical format
4. Split the dataset into training and testing sets using stratified sampling
5. Applied TF-IDF vectorization to transform SMS text data
6. Trained a Multinomial Naive Bayes classifier
7. Evaluated the model using accuracy, ROC-AUC score, and classification report
8. Tested the model on new SMS input

## Model Performance
- Accuracy: ~97%
- ROC-AUC Score: ~0.99

The model demonstrates high effectiveness in identifying spam messages.

## Output
- Classification of SMS messages as Spam or Ham
- Spam probability score for input messages

## Author
Yukthi N T
