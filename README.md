Titanic Classification Project

Overview

This project involves predicting the survival of passengers aboard the Titanic using various machine learning models. The dataset used is the Titanic dataset from Kaggle, which contains information such as age, fare, passenger class, and more.

Dataset
The dataset contains the following features:

PassengerId: Unique ID for each passenger
Pclass: Passenger class (1st, 2nd, 3rd)
Name: Passenger's name
Sex: Gender of the passenger
Age: Passenger's age
SibSp: Number of siblings/spouses aboard
Parch: Number of parents/children aboard
Ticket: Ticket number
Fare: Price of the ticket
Cabin: Cabin number 
Embarked: Port of embarkation (C, Q, S)
Survived: Target variable (0 = No, 1 = Yes)

Models Used
The following machine learning models were implemented and evaluated:

Logistic Regression
Random Forest Classifier
XGBoost Classifier
LightGBM Classifier
Support Vector Machine (SVM)
Multi-layer Perceptron (MLP)
Voting Classifier (Ensemble Model)
Bagging Classifier (Ensemble Model)

Implementation
Data Preprocessing
Handling missing values
Feature engineering (encoding categorical variables, feature scaling)
Splitting the dataset into training and testing sets

Model Training & Evaluation
Training each model on the training set by Evaluating accuracy
Comparing model performance and selecting the best model

Results
After evaluating multiple models, the XGBClassifier achieved the best performance with an accuracy of 0.8324022346368715
