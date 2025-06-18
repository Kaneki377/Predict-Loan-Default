# Predict-Loan-Default
Machine Learning Practice
# Credit Risk Prediction using Machine Learning

This repository contains a machine learning project based on the Kaggle dataset [Give Me Some Credit](https://www.kaggle.com/datasets/c/GiveMeSomeCredit), aiming to predict whether a person will experience serious financial distress (i.e., default on a loan) within the next two years.

## 📌 Problem Statement

Accurately assessing the creditworthiness of borrowers is critical for financial institutions. This project builds predictive models to estimate the likelihood that a consumer will become 90 days past due or worse on any credit obligation in the next 24 months.

## 🎯 Objectives

- Develop binary classification models to predict serious delinquency.
- Evaluate model performance using metrics such as ROC-AUC and F1-score.
- Support lenders in reducing default risk and improving loan approval decisions.

## 🔍 Dataset Overview

- Source: [Give Me Some Credit – Kaggle](https://www.kaggle.com/datasets/c/GiveMeSomeCredit)
- Target variable: `SeriousDlqin2yrs` (1 = serious delinquency, 0 = otherwise)
- Key features:
  - `RevolvingUtilizationOfUnsecuredLines`
  - `DebtRatio`
  - `NumberOfTime30-59DaysPastDueNotWorse`
  - `NumberOfOpenCreditLinesAndLoans`
  - `NumberOfTimes90DaysLate`
  - `NumberRealEstateLoansOrLines`
  - `NumberOfDependents`
  - (and others)

## 🛠️ Models Used

- Logistic Regression
- Random Forest
- Gradient Boosting (e.g., XGBoost or similar)

## 📈 Evaluation Metrics

- ROC-AUC Score
- F1-Score
- Confusion Matrix
- Classification Report


