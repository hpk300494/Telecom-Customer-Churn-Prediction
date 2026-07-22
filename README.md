# Telecom Customer Churn Prediction

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---

## Project Overview

Customer churn is one of the biggest challenges in the telecom industry. Since acquiring a new customer costs significantly more than retaining an existing one, accurately predicting churn helps companies proactively retain high-value customers.

This project develops machine learning models to identify high-value telecom customers who are likely to churn, using customer usage and recharge history.

---

## Business Problem

The objective is to:

- Predict whether a high-value customer will churn.
- Identify the most important factors contributing to churn.
- Help telecom companies improve customer retention strategies.

---

## Dataset

The dataset contains customer activity over four months.

The first three months are used to predict customer churn in the fourth month.

Key preprocessing steps include:

- Missing value treatment
- Feature engineering
- High-value customer filtering
- Churn tagging
- PCA for dimensionality reduction
- Handling class imbalance

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- PCA
- Logistic Regression
- Random Forest
- Decision Tree

---

## Project Workflow

1. Data Cleaning
2. Exploratory Data Analysis
3. Feature Engineering
4. High Value Customer Selection
5. Churn Label Creation
6. PCA
7. Model Building
8. Hyperparameter Tuning
9. Model Evaluation
10. Feature Importance Analysis
11. Business Recommendations

---

## Models Implemented

- Logistic Regression
- Decision Tree
- Random Forest
- PCA-based Classification Models

---

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Confusion Matrix

---

## Key Insights

- High-value customers contribute most of the telecom revenue.
- Declining call usage and recharge activity are strong indicators of churn.
- PCA effectively reduces dimensionality while maintaining predictive performance.
- Feature importance analysis identifies critical variables influencing churn.

---

## Repository Structure

```
telecom-customer-churn-prediction/
│
├── notebooks/
├── data/
├── images/
├── docs/
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

## Future Improvements

- XGBoost
- LightGBM
- CatBoost
- SHAP Explainability
- Hyperparameter Optimization
- Model Deployment using Streamlit

---

## Author

**Hanaa Parvez Khan**

M.Sc. Data Science

Machine Learning | Data Science | Predictive Analytics
