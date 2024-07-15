# Income Prediction

## Overview
This project aims to predict whether an individual's income exceeds $50K/yr based on the provided data. We uased a RandomForestClassifier for classification tasks and perform several pre-processing steps to handle categorical data and missing values.

## Dataset
- [The dataset](https://www.kaggle.com/datasets/wenruliu/adult-income-dataset)

The dataset used is the "Adult" dataset from the UCI Machine Learning Repository. It contains 48,842 instances with 14 attributes plus the income target variable.

The dataset consists of:
Features: Age, Workclass, fnlwgt, Education, Educational-num, Marital-status, Occupation, Relationship, Race, Gender, Capital-gain, Capital-loss,Hours-per-week, Native-country.
Target: Income

## Preprocessing
- Handling Missing Values: Missing values in the dataset are replaced with the mode for categorical variables and the median for numerical variables.
- Encoding: Categorical variables are converted into numerical representations using one-hot encoding.
- Feature Scaling: Numerical features are scaled to ensure they are on a similar scale.

## Model Training
The RandomForestClassifier is used as our model. The training process involves the following steps:
- Initialization: Initialize the RandomForestClassifier with desired hyperparameters.
- Training: Fit the model on the training data using the fit method.
- Hyperparameter Tuning: Use cross-validation and grid search to find the best hyperparameters for the model.
## Libraries To run the notebook:
- pandas
- scikit-learn
- matplotlib
- seaborn 
