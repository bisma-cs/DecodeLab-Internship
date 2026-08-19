# 🚀 Fraud Detection using Machine Learning

## 📌 Project Overview

This project explores how machine learning can be used to identify potentially suspicious transactions.

The main challenge is **class imbalance**, where one class is much smaller than the other. To address this, the project uses **SMOTE** and compares two classification approaches: **Logistic Regression** and **Random Forest**.

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Imbalanced-learn
- Matplotlib
- Seaborn
- Google Colab

---

## 📊 Project Workflow

1. Data Loading
2. Data Exploration
3. Data Preprocessing
4. Feature Engineering
5. Fraud-Risk Target Creation
6. Train/Test Split
7. SMOTE
8. Logistic Regression
9. Random Forest
10. Hyperparameter Tuning
11. Model Evaluation

---

## 📈 Model Evaluation

The models are evaluated using:

- **Precision**
- **Recall**
- **F1-Score**
- **ROC-AUC**

These metrics are used because the project deals with an imbalanced classification problem.

---

## 🤖 Models Used

### Logistic Regression

Used as the baseline classification model.

### Random Forest

Used as an ensemble-based classification model for comparison and improved prediction performance.

---

## ⚖️ Handling Class Imbalance

**SMOTE (Synthetic Minority Over-sampling Technique)** is used to address the imbalance between the target classes.

SMOTE is applied within the machine learning pipeline to help prevent data leakage.

---

## 💡 Key Learnings

- Handling imbalanced datasets
- Applying SMOTE correctly
- Building Scikit-learn pipelines
- Training classification models
- Hyperparameter tuning with GridSearchCV
- Evaluating models using Precision, Recall, F1-Score and ROC-AUC
- Understanding the importance of avoiding data leakage

---

## 📁 Project Files

```text
Data-Science-project-2/
│
├── Data Science Project 2 – Fraud Detection Pipeline.ipynb
├── Dataset for Data Analytics(3).xlsx
└── README.md
