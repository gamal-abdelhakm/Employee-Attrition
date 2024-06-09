# Project Title: Employee Attrition Prediction

## Overview
This project aims to predict employee attrition using various machine learning algorithms. The objective is to identify employees who are likely to leave the company based on historical data. The dataset is analyzed using different classification models to determine the most effective algorithm for predicting attrition.

## Dataset
The dataset consists of employee records with various features that influence attrition. The target variable indicates whether an employee has left the company.

## Models Evaluated

Logistic Regression (LR)
Accuracy: 89.46%
Confusion Matrix: [[249, 6], [25, 14]]
Macro Avg F1-Score: 0.71
Weighted Avg F1-Score: 0.88

Support Vector Machine (SVM)
Accuracy: 88.78%
Confusion Matrix: [[255, 0], [33, 6]]
Macro Avg F1-Score: 0.60
Weighted Avg F1-Score: 0.85

K-Nearest Neighbors (KNN)
Accuracy: 86.05%
Confusion Matrix: [[252, 3], [38, 1]]
Macro Avg F1-Score: 0.49
Weighted Avg F1-Score: 0.81

Decision Tree Classifier (CART)
Accuracy: 78.57%
Confusion Matrix: [[222, 33], [30, 9]]
Macro Avg F1-Score: 0.55
Weighted Avg F1-Score: 0.79

Random Forest Classifier (RF)
Accuracy: 88.10%
Confusion Matrix: [[255, 0], [35, 4]]
Macro Avg F1-Score: 0.56
Weighted Avg F1-Score: 0.84

Gradient Boosting Classifier (GB)
Accuracy: 89.12%
Confusion Matrix: [[250, 5], [27, 12]]
Macro Avg F1-Score: 0.68
Weighted Avg F1-Score: 0.87

Extreme Gradient Boosting (XGBoost)
Accuracy: 87.07%
Confusion Matrix: [[245, 10], [28, 11]]
Macro Avg F1-Score: 0.65
Weighted Avg F1-Score: 0.85

Gaussian Naive Bayes (GNB)
Accuracy: 84.35%
Confusion Matrix: [[225, 30], [16, 23]]
Macro Avg F1-Score: 0.70
Weighted Avg F1-Score: 0.85

AdaBoost Classifier (ABC)
Accuracy: 87.07%
Confusion Matrix: [[244, 11], [27, 12]]
Macro Avg F1-Score: 0.66
Weighted Avg F1-Score: 0.86

## Key Findings
Logistic Regression achieved the highest accuracy (89.46%) and performed well across multiple metrics.
Although other models such as Gradient Boosting and Random Forest also showed strong performance, Logistic Regression was the most balanced in terms of precision, recall, and F1-score.

## Conclusion
Logistic Regression is the most effective model for predicting employee attrition in this study, demonstrating a strong balance between accuracy and other performance metrics. These predictive models can help organizations identify potential attrition risks and take proactive measures to retain valuable employees.
