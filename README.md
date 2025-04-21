# 🧠 Machine Learning Cases - Kaggle Datasets

This repository contains several **Machine Learning cases** using public datasets from [Kaggle](https://www.kaggle.com/), focusing on **classification**, **class imbalance**, **threshold adjustment**, **complete pipelines**, and **specific metrics like Recall and Precision**, especially in problems such as **fraud detection**.

---

## Prerequisites

- Python 3.10+
- Scikit-learn
- Pandas
- Numpy
- Matplotlib & Seaborn
- Imbalanced-learn (SMOTE, TomekLinks, RandomUnderSampler)
- Jupyter Notebook

---

## Applied

- Exploratory Data Analysis (EDA)
- Preprocessing (scaling, imputation, encoding)
- Class balancing:
  - `RandomUnderSampler`
  - `SMOTE`
  - `Tomek Links`
- Pipeline creation
- Threshold adjustment to maximize specific metrics (e.g., Recall for fraud)
- Cross-validation with `cross_val_score` and `StratifiedKFold`
- Evaluation with `classification_report`, `confusion_matrix`, `ROC-AUC`