# Brown_Data1030_Final_Project
📊 Diabetes Prediction — Data1030 Final Project

This repository contains the full code, analysis, and results for the Diabetes Prediction Project, completed as the final deliverable for DATA 1030: Hands-On Data Science.
The goal of the project is to build an interpretable machine learning pipeline for predicting diabetes using clinical and demographic features. The workflow includes preprocessing, handling class imbalance, cross-validation, hyperparameter tuning, and model interpretability analysis.

🧠 Project Overview

This project follows an end-to-end machine learning process:

EDA: Distribution analysis, missingness patterns, class imbalance.

Preprocessing:

Iterative imputation for BMI

StandardScaler for numeric variables

One-hot encoding for categorical variables

Optional SMOTE oversampling applied only within cross-validation folds

Splitting: Stratified 60/20/20 train/validation/test split

Models Evaluated: Logistic Regression, SVM, Random Forest, XGBoost

Evaluation Metric: Primary — F1 score; Secondary — precision, recall, accuracy

Interpretability: Permutation feature importance, XGBoost gain/cover, SHAP force plots
