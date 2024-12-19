# Loan-Approval-Risk-Project
AML Final Project: Financial Risk for Loan Approval

This repository contains the final project for **CS5785: Applied Machine Learning**. The project focuses on building and evaluating supervised machine learning models to predict the risk associated with loan approval decisions.

## Project Overview

The project aims to explore and implement various preprocessing techniques, handle class imbalance in the dataset, and compare the performance of multiple machine learning algorithms. The primary goal is to predict whether a loan application will be approved based on features like income, debt, credit history, and other financial metrics.

## Key Features

1. **Data Preprocessing**:
   - Handled missing values and duplicates.
   - Encoded categorical variables like `EmploymentStatus` and `EducationLevel`.
   - Scaled numerical features using Min-Max scaling.
   - Engineered new features such as:
     - `IncomeToDebt Ratio`
     - `LoanToNetWorth Ratio`
     - `DebtRiskScore`

2. **Class Imbalance Handling**:
   - Oversampling techniques like SMOTE and ADASYN were applied to balance the target variable (`LoanApproved`).

3. **Machine Learning Models**:
   - Models implemented and evaluated include:
        - Support Vector Machine 
        - Gradient Boosting 
        - XGBoost 
        - Logistic Regression 
        - AdaBoost 
        - Random Forrest 
        - Gaussian NB
        - Neural Network 
        - K-Nearest Neighbors 
   - Various data augmentation strategies were tested (e.g., SMOTE, ADASYN, GMM).

4. **Evaluation Metrics**:
   - Precision, Recall, F1-Score, and Accuracy metrics were used to compare model performance.

## File Structure

- **`AML_Updated.ipynb`**: Jupyter notebook containing the code for preprocessing, modeling, and evaluation.
- **`Final_Project_AML.pdf`**: Detailed project report including methods, results, and discussion.
- **`classification_metrics.xlsx`**: Table of evaluation metrics for the supervised models.
- **`README.md`**: This file.

## Results

The results indicate that the Random Forest and Gradient Boosting models performed best, achieving high accuracy and balanced metrics across classes. Feature engineering and oversampling significantly improved model performance.



