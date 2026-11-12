# Medical Insurance Cost Prediction

CA-4 Use-Case-Based Continuous Assessment: Supervised Machine Learning (SML), Symbiosis Institute of Technology.

**Harshit Divekar**, PRN 24070721012, B.Tech CSE

This project predicts a person's annual medical insurance charges from age, sex, BMI, number of children, smoking status and region. It is a regression problem on the [Medical Cost Personal Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance) from Kaggle.

## Contents
- `Medical_Insurance_Cost_Prediction.ipynb`: the full notebook, covering EDA, baseline models (Linear Regression, Decision Tree, KNN), Random Forest, Gradient Boosting, XGBoost, GridSearchCV tuning, 5-fold cross-validation, residual analysis and feature importance
- `insurance.csv`: the dataset

## Result
Tuned XGBoost: test R² 0.875, RMSE $4,622, MAE $2,566 on a 30% hold-out set (Linear Regression baseline: R² 0.772).

## Run
```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost joblib
jupyter notebook Medical_Insurance_Cost_Prediction.ipynb
```
