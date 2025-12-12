# Real-Estate-Price-Prediction---Lasso-Ridge-Regression-Algorithm-Hyperparameter-Tuning-
This notebook applies Lasso and Ridge Regression with hyperparameter tuning to predict real estate prices using multiple property-related features.


## 🏘️ What This Notebook Does

* Loads and preprocesses real estate dataset
* Encodes categorical features & scales numerical values
* Trains **Lasso** and Ridge regression models
* Performs **Hyperparameter Tuning (GridSearchCV / similar)**
* Evaluates models using RMSE, R², and best parameters

---

## 📁 Files

* `Lasso_Ridge_Regression_Real_Estate_HPT.ipynb` — full workflow
* Real estate dataset (CSV) — required

---

## 🔧 Requirements

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

---

## ▶️ How to Run

```bash
jupyter notebook Lasso_Ridge_Regression_Real_Estate_HPT.ipynb
```

Make sure the dataset is in the same directory or update the file path in the notebook.

---

## 📊 Summary

This notebook helps you learn:

* Difference between Lasso & Ridge regularization
* How regularization improves model stability
* How to use hyperparameter tuning to find optimal α values
* How to evaluate regression models effectively

