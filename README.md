# Credit Scoring using Machine Learning Models

_Thesis Project – Loizidis Vasileios_  
_Department of Applied Mathematics and Physical Sciences, National Technical University of Athens_  
_Supervisor: Petros Stefaneas_  
_Date: November 2025_

---

## Overview

This project is part of my thesis and focuses on building and evaluating Machine Learning models for Credit Scoring —  
predicting the probability of default for loan applicants based on their financial and demographic characteristics.

The goal is to compare different ML approaches in terms of accuracy, interpretability, and practical value for credit risk assessment.

---

## Implemented Models

| Model | Description | Status |
|--------|--------------|--------|
| **Logistic Regression** | Baseline interpretable model for default prediction | Completed |
| **Support Vector Machine (SVM)** | Non-linear classifier for comparison | In progress |
| **Random Forest** | Ensemble-based tree model for robustness | In progress|
| **XGBoost** | Gradient boosting model for high predictive power | In progress|
|**Neural Networks** | Multilayer perceptron for capturing non-linear patterns | In progress|

---

## Current Notebook

File: CreditRiskThesis.ipynb

Includes:
- Data loading and preprocessing  
- Exploratory Data Analysis (EDA)  
- Handling missing values and scaling  
- Training the Logistic Regression model  
- Handling class imbalance with SMOTE  
- Model evaluation (Accuracy, Precision, Recall, F1, ROC-AUC)  
- Visualization and performance comparison  
- Conclusions  

---

## Objective

Develop a **reliable, interpretable, and data-driven ML pipeline**  
that helps financial institutions estimate default risk and support credit approval decisions.

---

## Tools & Libraries

- **Python (Google Colab)**  
- pandas, numpy, matplotlib, seaborn  
- scikit-learn (LogisticRegression, StandardScaler, train_test_split, metrics)  
- imbalanced-learn (SMOTE)  
- joblib (for model persistence)

---

