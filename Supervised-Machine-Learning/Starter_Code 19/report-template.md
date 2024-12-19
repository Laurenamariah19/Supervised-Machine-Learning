# Module 12 Report Template

# Overview of the Analysis

# Purpose of the Analysis

The purpose of this analysis was to evaluate machine learning models to predict the status of loans. Specifically, we aimed to classify loans as either 0 (healthy loans) or 1 (high-risk loans) to assist financial institutions in making better lending decisions.

# Financial Data

The dataset provided financial details about loans, including:

Loan size: The dollar amount borrowed.

Interest rate: The percentage charged on the loan.

Borrower income: The borrower’s annual income.

Debt-to-income ratio: Borrower’s total debt divided by their income.

Number of accounts: Total financial accounts the borrower holds.

Derogatory marks: Negative items on the borrower’s credit report.

Total debt: The borrower’s total outstanding debt.

The target variable was loan_status, which indicates whether a loan is healthy (0) or high-risk (1).

# Basic Data Distribution

Healthy loans (0): Majority of the data.

High-risk loans (1): Minority of the data.

# Machine Learning Process

Data Preparation:

Extracted the target variable (y) from the loan_status column.

Used the remaining columns as features (X).

Split the data into training and testing datasets using train_test_split.

Model Training:

Trained a Logistic Regression model using the training data (X_train and y_train).

Model Evaluation:

Used the testing data (X_test and y_test) to generate predictions.

Evaluated the model’s performance using a confusion matrix and classification report.

# Method Used

Logistic Regression: A simple and effective algorithm for binary classification tasks, well-suited for this analysis.

# Results

Machine Learning Model 1: Logistic Regression

Accuracy: 99%

Precision:

Class 0 (healthy loans): 1.00

Class 1 (high-risk loans): 0.84

Recall:

Class 0 (healthy loans): 0.99

Class 1 (high-risk loans): 0.94

F1-Score:

Class 0 (healthy loans): 1.00

Class 1 (high-risk loans): 0.89

# Summary

# Best Model

The Logistic Regression model stood out as the best-performing model. It was highly accurate and excelled at identifying healthy loans (0) while maintaining good performance for high-risk loans (1).