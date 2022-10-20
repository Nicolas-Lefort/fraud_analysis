# Fraud analysis

## Introduction
This document is a summary of a data analysis using python sklearn library.
The data come from: https://www.kaggle.com/code/girishvutukuri/exercise-insurance-fraud/data.

## Data exploration
The dataset contains 28836 points.
There are in total 46 features.
15 are numerical features.
30 are categorical features.
The target is: -ReportedFraud-.

## Models
The tested models are : 
- knn 
- svm 
- tree 
- naive bayes 
- logistic regression 
- random forest 

## Encoding
Numerical features are encoded using the RobustScaler.
Categorical features are one hot encoded.

## Results
The overall accuracy is about 90%. 
To be noted that the dataset is strongly unbalanced (mainly no Fraud labels).
Complete analysis in file "Fraud_analysis.ipynb".
