# FIN5016 Assignment 1-B: Credit Risk Classification Using Machine Learning

## Project Overview

This project aims to build a predictive model that classifies credit risk for loan applicants, using the UCI Default of Credit Card Clients dataset. The model predicts whether a client will default on the next payment, enabling financial institutions to make data-driven lending decisions.

## Contents

- `FIN5016_Assignment_1B.ipynb`: Main Jupyter Notebook with full code, analysis, and markdown explanations.
- `UCI_Credit_Card.csv`: Dataset used for training and evaluation.
- `README.md`: Project summary and usage guide.

## Key Steps Covered

- **Data Preprocessing**: Handling missing values, outliers, and encoding categorical variables
- **EDA**: Feature distributions, correlation heatmaps, and risk pattern insights
- **Feature Engineering**: Custom metrics like average bill, delay counts, and payment-to-bill ratios
- **Modeling**: Logistic Regression and Random Forest with 5-fold cross-validation
- **Evaluation**: Accuracy, F1-score, ROC curves, confusion matrices
- **Interpretation**: Feature importance, use in loan approval, and future improvement suggestions

## Models Used

- Logistic Regression
- Random Forest Classifier

## Highlights

- Random Forest outperformed Logistic Regression in recall, F1-score, and AUC
- Key predictors of default: PAY_0, LIMIT_BAL, TOTAL_DELAY_MONTHS
- Final model suitable for integration into loan approval systems

## Author

Joseph Clifford Muiruri  
FIN5016 – La Trobe University  
April 2025
