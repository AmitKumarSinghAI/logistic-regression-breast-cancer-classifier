# Logistic Regression – Breast Cancer Classifier

This project implements a binary classifier using **Logistic Regression** on the **Breast Cancer Wisconsin Dataset**, a popular dataset for binary classification tasks.

---

## 🔍 Objective

To build a machine learning model that classifies breast tumors as **malignant** or **benign** using logistic regression.

---

## 📦 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## 🗂️ Dataset

- **Source**: `sklearn.datasets.load_breast_cancer()` (no download required)
- **Target labels**:
  - `0`: Malignant (cancerous)
  - `1`: Benign (non-cancerous)

---

## 🚀 Workflow

1. Load breast cancer dataset
2. Split into training and testing sets
3. Standardize features using `StandardScaler`
4. Train logistic regression model
5. Make predictions and evaluate:
   - Confusion matrix
   - Precision, Recall, F1-score
   - ROC-AUC Score
   - Plot ROC Curve

---

## 📊 Model Performance

Confusion Matrix:
[[41 2]
[ 1 70]]

Precision: 0.9722
Recall: 0.9859
ROC-AUC Score: 0.9973



The model achieves **97.3% accuracy** with a near-perfect **ROC-AUC of 0.997**, demonstrating excellent classification performance.



## ▶️ How to Run

```bash
pip install pandas numpy scikit-learn matplotlib
python logistic_regression_app.py
