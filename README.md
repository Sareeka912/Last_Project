Data Science Project

Overview

This project involves analyzing and modeling three datasets: Credit Card Fraud, Customer Churn, and Breast Cancer. The main objectives is  to preprocess the data, handle class imbalance, and evaluate various machine learning models.

Imbalance Datasets

1. Credit Card Fraud Detection

Features: Various features related to credit card transactions.
Tasks: Data preprocessing, handling class imbalance, model evaluation.

2. Customer Churn Dataset

Features: LoyaltyID, Customer ID, Senior Citizen, Partner, Dependents, Tenure, Phone Service, Multiple Lines, Internet Service, Online Security, Online Backup, Device Protection, Tech Support, Streaming TV, Streaming Movies, Contract, Paperless Billing, Payment Method, Monthly Charges, Total Charges, Churn.
Tasks: Data preprocessing, handling class imbalance, feature selection, model evaluation.

3. Breast Cancer Dataset

Features: Various numerical and categorical features related to breast cancer diagnosis.
Tasks: Data preprocessing, outlier detection, handling class imbalance, feature selection, model evaluation.

Data Preprocessing

Handling Missing Values: Imputation and removal of missing values.
Feature Scaling: Standardization using StandardScaler to ensure uniform feature contribution.


Feature Engineering:

Polynomial Features: Generation of interaction and polynomial features to capture non-linear relationships.
Feature Selection: Using RFE (Recursive Feature Elimination) to select important features.

Class Imbalance Handling

Using Class Weights: Applied class weights to classifiers that support it (e.g., Logistic Regression, Decision Tree).
Simulated Balanced Distribution: Visualization of class distribution to understand the effect of class imbalance handling.
Other Techniques: Various techniques to handle class imbalance, such as adjusting class weights and evaluating the effect on model performance.

Model Evaluation

Baseline Performance: Evaluation of classifiers before feature engineering.
Performance After Feature Engineering: Re-evaluation of classifiers to assess the impact of feature engineering.

Metrics:

Classification Report: Precision, recall, F1-score for each class.
ROC-AUC: Area under the Receiver Operating Characteristic curve.
PR-AUC: Area under the Precision-Recall curve.
Class Distribution Visualization
Before Handling Class Imbalance: Bar plots showing the class distribution in the original dataset.
After Handling Class Imbalance: Bar plots showing the adjusted class distribution after applying class imbalance handling techniques.

Dependencies

Python 3.x
scikit-learn
pandas
numpy
matplotlib
seaborn
