# Cardiovascular Disease Risk Prediction 🏥

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1.0+-orange.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

## 📋 Project Overview

Machine learning classification pipeline predicting cardiovascular disease risk from routine clinical measurements. Compared **5 algorithms** on **68,615 patient records**.

**Best Model:** Random Forest — **73.53% accuracy**, **0.804 ROC-AUC**

---

## 🎯 Results

| Model | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|-------|----------|-----------|--------|----------|---------|
| **Random Forest** | **73.53%** | 75.97% | 68.02% | 71.77% | **0.804** |
| SVM (RBF) | 73.26% | 76.00% | 67.17% | 71.31% | 0.792 |
| Decision Tree | 73.07% | 76.55% | 65.68% | 70.70% | 0.796 |
| Logistic Regression | 72.86% | 75.04% | 67.64% | 71.15% | 0.796 |
| KNN | 72.20% | 73.08% | 69.36% | 71.17% | 0.783 |

**Top Predictive Features:** Systolic BP · Age · Diastolic BP

---

## 🛠️ Tech Stack

Python · pandas · numpy · scikit-learn · matplotlib · seaborn · joblib

**Algorithms:** Random Forest, SVM, Decision Tree, Logistic Regression, KNN  
**Techniques:** Feature Engineering, GridSearchCV, Cross-Validation, ROC Analysis

---

## 📊 Dataset

- **Source:** Cardio Train Dataset
- **Size:** 70,000 → 68,615 after cleaning
- **Features:** Age, BP, BMI, cholesterol, glucose, lifestyle factors

---

## 🔄 Workflow

1. **Preprocessing:** Removed 1,385 invalid records
2. **Feature Engineering:** BMI, pulse pressure
3. **EDA:** 10+ visualizations
4. **Modeling:** 5 algorithms with hyperparameter tuning
5. **Evaluation:** Cross-validation, confusion matrices, ROC curves

---

## 📈 Key Insights

- Disease rate doubles from <40 age group to 60+
- High BP (>140): **85.8% disease rate** vs 31.6% normal
- ~73% ceiling expected with routine vitals alone

---

## 🚀 How to Run

```bash
git clone https://github.com/codevaper/cardio-disease-prediction.git
cd cardio-disease-prediction
pip install -r requirements.txt
jupyter notebook cardio_disease_prediction.ipynb
