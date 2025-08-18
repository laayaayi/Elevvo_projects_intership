 📌 Project 1: Student Score Prediction
**Goal:**
Predict students' exam scores based on study hours and related features.

**Steps:**
- Data cleaning and handling missing values.
- Exploratory Data Analysis (EDA) to understand patterns.
- Feature scaling for better model performance.
- Model: Linear Regression for continuous target prediction.
- Evaluation: Mean Squared Error (MSE), R² score.

---

 📌 Project 2: Loan Approval Classification
**Goal:**
Classify whether a loan application will be approved or rejected.

**Steps:**
- Data preprocessing and encoding categorical variables.
- Handling class imbalance with **SMOTE**.
- Feature scaling with **StandardScaler**.
- Model: Logistic Regression with adjusted `max_iter`.
- Evaluation: Confusion Matrix, Precision, Recall, F1-score.

---

## 🛠 Tools & Libraries
- Python, Pandas, NumPy
- Matplotlib, Seaborn
- scikit-learn
- imbalanced-learn (SMOTE)

  ----

  📌 Project 3:# 🛒 Walmart Sales Forecasting with Time Series Regression

This project uses historical sales data from Walmart to forecast future weekly sales using time series regression techniques. It includes feature engineering, seasonal decomposition, rolling averages, and time-aware validation with XGBoost and LightGBM.

---

## 📦 Dataset

- **Source**: [Walmart Store Sales Forecasting (Kaggle)](https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting/data)
- **File Used**: `train.csv`
- **Target Variable**: `Weekly_Sales`

---

## 🧠 Covered Topics

- Time Series Forecasting  
- Regression Modeling  
- Feature Engineering (Lag, Rolling Mean, Date Features)  
- Seasonal Decomposition  
- Time-Aware Cross Validation  
- XGBoost & LightGBM

---

## 🛠️ Tools & Libraries

- Python  
- Pandas  
- Matplotlib  
- Scikit-learn  
- XGBoost  
- LightGBM  
- Statsmodels

---

## 📈 Workflow Overview

1. **Data Preprocessing**  
   - Group sales by date  
   - Sort chronologically  
   - Handle missing values

2. **Feature Engineering**  
   - Rolling averages (7-day, 30-day)  
   - Lag features  
   - Seasonal decomposition (trend, seasonal)

3. **Modeling**  
   - TimeSeriesSplit for validation  
   - Train XGBoost and LightGBM regressors  
   - Evaluate using RMSE

4. **Visualization**  
   - Plot actual vs predicted sales over time

---



