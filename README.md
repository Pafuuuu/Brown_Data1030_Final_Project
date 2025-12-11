# 📊 Diabetes Prediction — Data1030 Final Project

This repository contains the full code, analysis, and results for the **Diabetes Prediction Project**, completed as the final deliverable for *DATA 1030: Hands-On Data Science*.  
The goal of the project is to build an interpretable machine learning pipeline for predicting diabetes using clinical and demographic features. The workflow includes preprocessing, handling class imbalance, cross-validation, hyperparameter tuning, and model interpretability analysis.

---

## 🧠 Project Overview

This project follows an end-to-end machine learning process:

- **EDA:** Distribution analysis, missingness patterns, class imbalance.
- **Preprocessing:**  
  - Iterative imputation for BMI  
  - StandardScaler for numeric variables  
  - One-hot encoding for categorical variables  
  - Optional SMOTE oversampling applied only within cross-validation folds
- **Splitting:** Stratified **60/20/20** train/validation/test split  
- **Models Evaluated:** Logistic Regression, SVM, Random Forest, XGBoost  
- **Evaluation Metric:** Primary — **F1 score**; Secondary — precision, recall, accuracy  
- **Interpretability:** Permutation feature importance, XGBoost gain/cover, SHAP force plots

---

## 🛠️ Environment Setup

This project uses a conda environment for full reproducibility.

### `environment.yml`

```yaml
name: data1030
channels:
- conda-forge
dependencies:
- python = 3.12.10
- numpy = 2.2.5
- matplotlib = 3.10.1
- seaborn = 0.13.2
- pandas = 2.2.3
- polars = 1.27.1
- scikit-learn = 1.6.1
- py-xgboost = 3.0.0
- shap = 0.47.2
- jupyter
```
## 📁 Repository Structure
```
prefix: /opt/conda
├── data/
│      └── diabetes_prediction_dataset.csv                  
├── src/
│   └── final_project.ipynb 
├── figures/
│   └── *.png                    
├── report/
│   └── Data1030_Final_Report.pdf
├── data1030.yml
└── README.md
```
## 👤 Author

Xuanyao (Clark) Qian
Brown University, Data Science Institute

GitHub: https://github.com/Pafuuuu

Email: xuanyao_qian@brown.edu


## 📄 License

This repository is provided for academic and educational use under the MIT License.

