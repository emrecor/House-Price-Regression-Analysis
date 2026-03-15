# House Price Prediction & Regression Analysis

This repository contains an end-to-end data science project focused on predicting residential home prices using advanced regression techniques. The project covers the entire pipeline, from comprehensive Exploratory Data Analysis (EDA) to hyperparameter optimization.

## 📌 Project Overview
The goal of this project is to predict the sales price of houses based on 79 explanatory variables. It demonstrates the application of modern machine learning algorithms and rigorous feature engineering to solve a high-dimensional regression problem.

## 🛠️ Tech Stack & Tools
- **Language:** Python
- **Data Manipulation:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn, XGBoost, CatBoost
- **Optimization:** Optuna (Bayesian Optimization)
- **Statistical Analysis:** SciPy (Skewness/Kurtosis correction)

## 🚀 Key Features of the Analysis
- **Advanced Preprocessing:** - Systematic handling of missing values based on feature context.
    - Log-transformation of the target variable to ensure normality and improve model stability.
    - Encoding of categorical variables and feature scaling.
- **Modeling Strategy:** - Implementation of high-performance Gradient Boosting algorithms: **XGBoost** and **CatBoost**.
    - Cross-validation with **K-Fold** to ensure model robustness.
- **Hyperparameter Tuning:** - Used **Optuna** for automated hyperparameter search, significantly reducing the Root Mean Squared Error (RMSE).
- **Ensemble Approach:** - Weighted averaging of model predictions to achieve better generalization on unseen data.

## 📊 Performance
The models were evaluated using **RMSE** on log-transformed prices:
- **CatBoost Average RMSE:** ~1.126
- **XGBoost Average RMSE:** ~1.126

## 📂 Project Structure
```text
├── notebooks/
│   └── price_prediction_analysis.ipynb  # Main analysis and modeling notebook
└── README.md                            # Project documentation
