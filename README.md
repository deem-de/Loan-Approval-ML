# Loan Approval Prediction Using Machine Learning

## Overview

This project develops a machine learning pipeline to predict loan approval decisions based on applicant financial and demographic information.

The project covers the complete machine learning workflow, including data preprocessing, feature engineering, model training, hyperparameter tuning, performance evaluation, and model explainability using SHAP.

---

## Problem Statement

Financial institutions receive thousands of loan applications and need efficient methods to evaluate applicant eligibility.

The goal of this project is to build a classification model capable of predicting whether a loan application should be approved or rejected based on applicant attributes.

---

## Dataset

The dataset contains approximately 52,000 loan applications with multiple applicant-related features, including:

- Income
- Employment Status
- Credit Score
- Loan Amount
- Loan Term
- Existing Debt
- Financial History
- Demographic Information

### Target Variable

Loan Approval Status

- 1 = Approved
- 0 = Rejected

---

## Project Pipeline

### 1. Data Preparation

- Data loading
- Missing value handling
- Data cleaning
- Duplicate checking
- Feature selection
- Data leakage prevention

### 2. Exploratory Data Analysis

- Distribution analysis
- Correlation analysis
- Class balance inspection
- Feature relationship visualization

### 3. Feature Engineering

- Encoding categorical variables
- Scaling numerical features
- Outlier handling
- Feature transformation

### 4. Model Development

Several machine learning models were trained and evaluated:

- Logistic Regression
- Decision Tree
- Random Forest
- AdaBoost
- Gradient Boosting
- XGBoost

### 5. Hyperparameter Tuning

Grid Search and optimization techniques were applied to improve model performance.

### 6. Model Evaluation

Performance was assessed using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC

---

## Explainable AI (XAI)

To improve transparency and trustworthiness, SHAP (SHapley Additive Explanations) was used to:

- Interpret model predictions
- Measure feature importance
- Explain individual decisions
- Improve model transparency

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost
- SHAP
- Jupyter Notebook

---

## Repository Structure

```text
Loan-Approval-ML/
│
├── ML_Final_Phase.ipynb
├── LoanDataSet.zip
├── README.md
├── requirements.txt
└── images/
```

---

## Key Learning Outcomes

Through this project, I gained practical experience in:

- End-to-end Machine Learning workflows
- Data preprocessing techniques
- Classification algorithms
- Model optimization
- Explainable AI (SHAP)
- Real-world predictive analytics

---

## Author

**Deem Alrashoud**

Computer Science Student | Artificial Intelligence Enthusiast
