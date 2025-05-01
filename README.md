# 📊 Loan Amount Prediction Using Simple Linear Regression

## 📌 Project Overview

This project focuses on predicting loan amounts for bank customers based on their annual income using **Simple Linear Regression**. It simulates a real-world scenario within the banking system where estimating loan disbursement accurately is critical.

---

## 🎯 Objective

To build and improve a machine learning model that can predict the loan amount a customer is likely to receive based on their annual income, ensuring high accuracy and optimal generalization.

---

## ⚙️ Workflow Summary

1. **Synthetic Dataset Creation**  
   A realistic dataset was generated to mimic customer profiles using annual income and corresponding loan amounts with some added noise.

2. **Exploratory Data Analysis (EDA)**  
   Visualized relationships between variables to confirm linearity between income and loan amount.

3. **Data Preprocessing**  
   - Splitting the data into training and testing sets.  
   - Standardizing features using `StandardScaler`.

4. **Model 1: Simple Linear Regression**  
   - Built a baseline model to predict loan amounts.  
   - Evaluated using metrics like R² Score and Mean Squared Error (MSE).

5. **Model 2: Ridge Regression (L2 Regularization)**  
   - Implemented to reduce overfitting.  
   - Hyperparameter tuning using **GridSearchCV** for the best alpha value.

6. **Model 3: Lasso Regression (L1 Regularization)**  
   - Used to shrink less important features (in case of multivariate).  
   - Hyperparameter tuning using **RandomizedSearchCV**.

7. **Model 4: Ridge Regression with Bayesian Optimization**  
   - Applied **BayesSearchCV** for efficient hyperparameter optimization over a continuous alpha space.  
   - Delivered the best performance with minimal computational cost.

---

## ✅ Techniques & Tools Used

- **Machine Learning Algorithms:**  
  - Simple Linear Regression  
  - Ridge Regression (L2)  
  - Lasso Regression (L1)  

- **Hyperparameter Tuning:**  
  - GridSearchCV  
  - RandomizedSearchCV  
  - Bayesian Optimization via BayesSearchCV

- **Libraries & Tools:**  
  - Python, NumPy, Pandas  
  - Matplotlib, Seaborn  
  - Scikit-learn  
  - scikit-optimize (skopt)

---

## 📈 Outcome

- Ridge Regression with **Bayesian Optimization** yielded the best performance.
- Regularization techniques and hyperparameter tuning significantly improved the baseline model.
- The project demonstrates a complete ML pipeline from data generation to model evaluation and optimization.

---
