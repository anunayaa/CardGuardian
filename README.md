 CardGuardian: Credit Card Fraud Detection Predictive Models

![fraud-detection](https://img.shields.io/badge/Domain-FinTech-blue.svg)
![status](https://img.shields.io/badge/Status-Completed-brightgreen.svg)
![python](https://img.shields.io/badge/Python-3.8%2B-yellow.svg)

Credit card fraud has become a major challenge for the financial industry with billions lost annually due to unauthorized transactions. This project, CardGuardian, implements and compares several machine learning models to detect fraudulent credit card transactions using a real-world, highly imbalanced dataset.

---

## 📌 Project Objectives

- To develop predictive models capable of identifying fraudulent transactions.
- To compare multiple machine learning algorithms based on performance metrics like precision, recall, F1-score, and ROC-AUC.
- To handle severe class imbalance using resampling techniques (SMOTE, undersampling).
- To visualize and interpret model results for actionable insights.

## 🧠 Machine Learning Models Used

- Random Forest
- CadBoost
- XGBoost
- LightGBM
- Adaboost

---

## 🛠 Key Techniques

- Exploratory Data Analysis (EDA) using Matplotlib, Seaborn, Plotly
- Feature scaling with StandardScaler
- Dimensionality reduction and correlation heatmaps
- Resampling Techniques:
  - SMOTE (Synthetic Minority Over-sampling Technique)
  - Random Undersampling
- Model Evaluation Metrics:
  - Precision, Recall, F1-Score
  - ROC-AUC and Confusion Matrix
  - Cross-validation

---

## 📈 Results Summary

- Models were evaluated under imbalanced condition.
- SMOTE and undersampling significantly improved recall and F1-score for most classifiers.
- XGBoost and Random Forest yielded the best trade-off between detection accuracy and false positives.

---

## 🔧 Installation and Setup

1. Clone this repository:
      git clone https://github.com/anunayaa/cardguardian-creditcard-fraud.git
   cd cardguardian-creditcard-fraud


2. Create a virtual environment (optional but recommended):

   bash
   python -m venv env
   source env/bin/activate   # or `env\Scripts\activate` on Windows
   


3. Run the notebook:

      jupyter notebook Credit_Card_Fraud_Detection_Predictive_Models.ipynb
   

---

## 📁 Repository Structure

├── Credit_Card_Fraud_Detection_Predictive_Models.ipynb
├── README.md


---

## 📬 Contact

Author: Anunaya R Pillai
---

⭐️ Star this repo if you found it useful!




