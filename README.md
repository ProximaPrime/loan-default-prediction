# 🏦 Loan Default Prediction — Credit Risk Modeling

![Python](https://img.shields.io/badge/Python-3.7+-blue)
![ML](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange)
![Status](https://img.shields.io/badge/Project-Completed-success)

---

## 📌 Project Overview

This project builds a machine learning model to predict the probability of loan default using borrower financial and demographic data.

It simulates a **real-world credit risk scoring system**, focusing on ranking borrowers by risk level.

---

## 🎯 Objective

* Predict borrower default probability
* Build a clean, reproducible ML pipeline
* Apply financial feature engineering
* Deliver submission-ready predictions

---

## 📊 Dataset Summary

* ~255,000 training samples
* ~109,000 test samples
* Target imbalance: ~11.6% default rate

---

## ⚙️ Pipeline

### 🔹 Data Processing

* Removed identifiers
* Encoded categorical variables using risk encoding
* Handled missing values

---

### 🔹 Feature Engineering

Engineered domain-driven features:

* Debt Burden
* Income Buffer
* Risk Index
* Credit Risk Score
* Stability Score
* Log transformations

---

### 🔹 Model

**ExtraTreesClassifier**

Why:

* Strong tabular performance
* Handles non-linear relationships
* Robust to noise

---

## 📈 Performance

* **ROC AUC: ~0.75**

This reflects moderate predictive signal due to limited feature separability.

---

## 📊 Feature Importance

Top drivers of default risk include:

* Debt burden
* Interest rate
* Loan amount
* Age

---

## 🧠 Key Insights

* Feature engineering is more impactful than model choice
* Financial ratios significantly improve prediction
* Dataset has moderate signal → limits maximum AUC

---

## 🚀 Future Improvements

* Add credit history data
* Use time-based repayment features
* Apply gradient boosting models
* Deploy as an API or dashboard

---

## 🛠️ Tech Stack

* Python
* Pandas / NumPy
* Scikit-learn
* Matplotlib

---

## 📁 Project Structure

```
notebook/
README.md
Requirements.txt/
output/
```

---

## 👤 ABIODUN ADETEYE

DATA SCIENTIST

---

## ⭐ Notes

This project demonstrates a full end-to-end ML workflow with a focus on:

* Clean structure
* Reproducibility
* Real-world applicability

---

⭐ Star this repo if you found it useful!
