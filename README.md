# credit-card-fraud-detection
CREDIT CARD FRAUD DETECTION USING THE MACHINE LEARNING MODELS 
CREDIT CARD FRAUD DETECTION PROJECT

Introduction

This project aims to build a machine learning model to identify fraudulent credit card transactions. The dataset used for this project contains transaction data, and we will preprocess and normalize the data, handle class imbalance issues, and split the dataset into training and testing sets. We will train a classification algorithm, such as logistic regression or random forests, to classify transactions as fraudulent or genuine. Finally, we will evaluate the model's performance using metrics like precision, recall, and F1-score. Techniques like oversampling or undersampling will be considered for improving the results.

Dataset

The dataset used for this project contains transaction data and includes the following features:

Time: Number of seconds elapsed between this transaction and the first transaction in the dataset
V1-V28: Result of a PCA transformation to protect sensitive information in the dataset
Amount: Transaction amount
Class: Whether the transaction is fraudulent (1) or genuine (0)
Libraries Used

numpy
pandas
matplotlib
seaborn
scikit-learn
Models Used

Random Forest Classifier
Logistic Regression
Code Overview

Importing Required Libraries and Dataset
Data Preprocessing
Handling Missing Values
Normalizing Data
Handling Class Imbalance
Exploratory Data Analysis (EDA)
Visualizing Class Distribution
Model Building
Random Forest Classifier
Logistic Regression
Model Evaluation

Both Random Forest Classifier and Logistic Regression models were evaluated using accuracy, confusion matrix, and classification report.

Conclusion

In this project, we developed machine learning models to identify fraudulent credit card transactions. We used the Random Forest Classifier and Logistic Regression algorithms for prediction and evaluated their performance. The Random Forest Classifier achieved an accuracy of 99%, while the Logistic Regression model achieved an accuracy of 99%.
