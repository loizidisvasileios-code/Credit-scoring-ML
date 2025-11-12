[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/loizidisvasileios-code/Credit-scoring-ML/blob/main/CreditRiskThesis.ipynb)


# Credit Risk using ML models

_Thesis Project – Loizidis Vasileios_  
_Department of Applied Mathematics and Physical Sciences, National Technical University of Athens_  
_Supervisor: Petros Stefaneas_  
_Date: November 2025_

---

## How to run
1. Open in Colab.
2. Data loading: Kaggle “Give Me Some Credit” (cs-training.csv).
3. Run the cells by order: EDA → preprocessing (impute/scale) → Logistic Regression (baseline & SMOTE) → evaluation.

*Target:* SeriousDlqin2yrs (0/1)  
*Class imbalance:* ~7% positive → αντιμετώπιση με SMOTE &/or class_weight='balanced'.  
*Metrics:* Accuracy, Precision, Recall, F1, ROC–AUC.  
*Reproducibility:* random_state=42 σε split/SMOTE/estimators.

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

Develop a reliable, interpretable, and data-driven ML pipeline 
that helps financial institutions estimate default risk and support credit approval decisions.

---

## Tools & Libraries

- Python (Google Colab)  
- pandas, numpy, matplotlib, seaborn  
- scikit-learn (LogisticRegression, StandardScaler, train_test_split, metrics)    
- joblib (for model persistence)

---

