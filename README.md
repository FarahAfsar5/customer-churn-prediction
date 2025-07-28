# customer-churn-prediction
 "ML project to predict bank customer churn"

# Customer Churn Prediction using Random Forest

This project predicts whether a customer will **exit** (churn) from a bank using historical customer data. The model uses a **Random Forest Classifier** for classification.

---

## 📌 Project Overview

- **Dataset:** `Churn_Modelling.csv` (from Kaggle)
- **Language:** Python (Colab Notebook)
- **Libraries:** pandas, seaborn, matplotlib, scikit-learn
- **ML Model Used:** Random Forest Classifier
- **Goal:** Predict if a customer will **churn (exit)** or **stay**.

---

##  Dataset Description

The dataset includes various features such as:

- `CreditScore`, `Geography`, `Gender`, `Age`, `Tenure`, `Balance`, etc.
- The target variable is: `Exited`  
  - `0`: Customer stayed  
  - `1`: Customer exited (churned)

---

##  Steps Performed

1. **File Upload** via Google Colab
2. **Data Cleaning:**
   - Removed irrelevant columns: `RowNumber`, `CustomerId`, `Surname`
3. **Encoding:**
   - `Gender` → Label Encoding
   - `Geography` → One-Hot Encoding
4. **Train-Test Split (80-20)**
5. **Model Training** using Random Forest Classifier
6. **Evaluation:**
   - Accuracy score
   - Confusion Matrix
7. **Feature Importance** Visualization

---

##  Model Performance

- **Accuracy:** ~80% (depending on randomness and parameters)
- **Confusion Matrix:** Shows true positives, true negatives, etc.
- **Important Features:** Age, Balance, Number of Products, etc.

---

---

## 🚀 How to Run

1. Open the Colab notebook.
2. Upload `Churn_Modelling.csv` when prompted.
3. Run all cells to see:
   - Model training
   - Accuracy score
   - Confusion matrix
   - Feature importance plot

---



