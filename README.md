# Predictive Lead Conversion Analysis

## Overview

Developed an end-to-end machine learning solution to predict lead conversion and identify the key factors influencing customer acquisition. The project combines exploratory data analysis, feature engineering, predictive modeling, and interactive business intelligence dashboards to support data-driven sales and marketing decisions.

---

## Business Problem

Organizations generate thousands of leads through multiple campaigns, but only a small percentage convert into customers. The objective of this project is to:

- Predict lead conversion using machine learning
- Identify high-performing lead sources and campaigns
- Analyze sales representative performance
- Build dashboards for business stakeholders

---

## Tech Stack

**Programming**
- Python
- Pandas
- NumPy

**Machine Learning**
- Scikit-learn
- XGBoost
- SMOTE

**Visualization**
- Matplotlib
- Seaborn
- Power BI
- Tableau
- Excel

---

## Project Workflow

```
Raw Data
      ↓
Exploratory Data Analysis
      ↓
Data Cleaning & Feature Engineering
      ↓
Machine Learning
      ↓
Model Evaluation
      ↓
Business Dashboards
```

---

## Exploratory Data Analysis

Performed exploratory analysis to identify patterns affecting lead conversion, including:

- Lead stage distribution
- Lead source performance
- Campaign effectiveness
- Sales executive performance
- Conversion trends
- Missing value analysis

---

## Feature Engineering

Created business-focused features including:

- Lead Age
- Interaction Hours
- First Contact Delay
- Contacted Status
- Follow-up Status

---

## Machine Learning Models

Models evaluated:

- Logistic Regression
- Logistic Regression (SMOTE)
- XGBoost Classifier

Evaluation Metrics:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Confusion Matrix

---

## Results

| Model | ROC-AUC |
|--------|---------|
| Logistic Regression | **0.916**  |
| Logistic Regression (SMOTE) | **0.920**  |
| XGBoost | **0.947** |

### Key Findings

- Addressed severe class imbalance using SMOTE.
- XGBoost achieved the highest ROC-AUC (0.947), delivering the best overall predictive performance.
- Feature engineering significantly improved model performance and interpretability.
- Interactive dashboards enabled analysis of campaign effectiveness, lead sources, and sales performance.

---

## Dashboards

Built interactive dashboards in:

- Excel
- Tableau
- Power BI

Key business insights include:

- Lead conversion trends
- Campaign performance
- Lead source analysis
- Sales executive performance
- KPI monitoring


---

## Repository Structure

```
├── data
├── notebooks
│   ├── 01_eda.ipynb
│   ├── 02_cleaning_feature_engineering.ipynb
│   └── 03_modeling.ipynb
├── images
├── README.md
└── requirements.txt
```

---

## Dataset

The dataset is not included in this repository due to confidentiality. The project structure and notebooks are provided for educational and portfolio purposes.

---

## Author

**Akhina Manual**
