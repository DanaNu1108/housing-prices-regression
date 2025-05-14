# 🏠 Housing Prices - Advanced Regression Techniques

This repository contains a full regression analysis and model experimentation based on the [Kaggle Housing Prices dataset](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques).  
The objective is to predict home sale prices using numerical and categorical features that describe residential properties in Ames, Iowa.

---

## 📂 Project Structure
```
├── Housing_Prices.ipynb # Full notebook: EDA, preprocessing, modeling
├── final_submission.csv # Output predictions (optional)
└── README.md # Project documentation
```

---

## 🗃 Dataset

The dataset is not included in this repository due to size limitations.  
You can download the data directly from Kaggle here:  
🔗 [Kaggle Dataset – House Prices: Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data)

---

## 📒 Project Overview

This is a supervised regression task with 79 explanatory variables covering property size, quality, location, and more.  
The notebook walks through data exploration, preprocessing, feature selection, and model evaluation.

---

## 📌 Key Insights

- Strong positive correlation found between `OverallQual`, `GrLivArea`, and `SalePrice`.
- Log transformation of `SalePrice` improved distribution and model performance.
- Missing values were handled through domain-specific imputation strategies.
- One-hot encoding was applied to categorical features with multiple levels.

---

## 🧠 Models Used

- Linear Regression – Baseline
- Ridge and Lasso Regression – Regularized models to handle multicollinearity
- Random Forest – Ensemble model with good balance of bias and variance
- XGBoost – High-performance gradient boosting model with lowest RMSE

---

## 🧪 Notebook Summary

- Exploratory Data Analysis (EDA)
- Data cleaning and missing value treatment
- Feature engineering and transformation
- Model training, comparison, and validation
- Evaluation metrics: RMSE, R²

---

## ✅ Final Notes

This project focuses on improving prediction performance through careful preprocessing and model tuning.  
Further improvements could include hyperparameter optimization with cross-validation and deploying the best model through a web app or dashboard.

