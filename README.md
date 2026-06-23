# Predictive Lead Conversion Analysis

## Project Overview
This project focuses on analyzing lead generation data and predicting whether a lead will convert into a customer. The project combines data cleaning, exploratory data analysis (EDA), dashboard creation, and machine learning techniques to generate business insights and improve lead conversion prediction.

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Excel
- Tableau
- Power BI

## Project Workflow

1. Data Cleaning and Feature Engineering
- Removed irrelevant columns
- Handled missing values
- Converted date columns to datetime format
- Created new features such as:
     - Interaction Hours
     - First Contact Delay Hours
     - Lead Age
     - Contacted Status
     - Follow-up Status

2. Exploratory Data Analysis (EDA)
- Lead conversion distribution analysis
- Lead source performance analysis
- Campaign performance analysis
- Salesperson-wise conversion analysis

3. Machine Learning Models

The following models were trained and evaluated:

- Logistic Regression
- Logistic Regression with SMOTE
- XGBoost Classifier

4. Model Evaluation

Models were compared using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix
- ROC Curve

## Key Findings
- The dataset was highly imbalanced, making accuracy alone an unreliable metric.
- Logistic Regression achieved the highest accuracy but failed to identify many converted leads due to low recall.
- Applying SMOTE significantly improved recall, helping identify more potential conversions.
- XGBoost achieved the highest ROC-AUC score (0.947) and provided the best balance between identifying converted leads and overall predictive performance.
- Based on the evaluation metrics, XGBoost was selected as the preferred model for lead conversion prediction.

## Dashboard Development

Interactive dashboards were created using:

Excel
Tableau
Power BI

The dashboards provide insights into:

- Lead source performance
- Campaign effectiveness
- Conversion trends
- Sales performance

## Dataset

The dataset used for this project is not included in this repository due to privacy considerations.

## Author

Akhina Manual