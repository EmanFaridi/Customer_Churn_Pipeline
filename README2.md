# Task 2: Customer Churn Prediction Pipeline

## Objective
Build a reusable machine learning pipeline for predicting customer churn using the Telco Churn dataset.

## Dataset
- Telco Customer Churn Dataset from Kaggle
- Features include customer demographics, services, and billing info
- Target: `Churn` (Yes/No)

## Methodology
1. Data cleaning and preprocessing:
   - Convert `TotalCharges` to numeric
   - Drop missing values
2. Train-test split (80-20)
3. Identify categorical and numerical columns
4. Build preprocessing pipelines:
   - Numerical → StandardScaler
   - Categorical → OneHotEncoder
5. Build ML pipeline with Logistic Regression
6. Train the pipeline
7. Evaluate using accuracy and classification report
8. Hyperparameter tuning using GridSearchCV
9. Save the pipeline using `joblib`

## Key Results
- Accuracy on test data: ~80%
- Best hyperparameters: `C` values from GridSearchCV