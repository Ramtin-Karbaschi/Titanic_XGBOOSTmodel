# Titanic Survival Prediction Model

## Project Overview
This repository contains a machine learning model designed to predict passenger survival outcomes from the Titanic disaster. The model utilizes the XGBoost classification algorithm with optimized hyperparameters to achieve high prediction accuracy.

## Dataset
The analysis is based on the famous Titanic dataset from Kaggle, which includes passenger information such as:
- Age
- Sex
- Passenger class
- Fare

## Methodology
The notebook implements a comprehensive machine learning workflow:

1. **Data Exploration and Visualization**
   - Correlation analysis between numerical features
   - Examination of survival rates by gender

2. **Data Preprocessing**
   - Removal of less relevant features (Embarked, Cabin, Ticket, etc.)
   - Encoding categorical variables
   - Handling missing values through mean imputation
   - Class imbalance correction using SMOTE (Synthetic Minority Over-sampling Technique)

3. **Model Development**
   - Implementation of XGBoost classifier
   - Hyperparameter optimization through GridSearchCV
   - Model evaluation using accuracy metrics

4. **Prediction Generation**
   - Application of the trained model to the test dataset
   - Creation of submission file for Kaggle competition

## Results
The model achieves strong predictive performance through careful feature selection and parameter tuning. Hyperparameter optimization significantly improved the model's accuracy compared to the baseline implementation.
