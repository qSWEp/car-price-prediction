# Car Price Prediction

Regression model predicting used-car prices, achieving **R² = 0.93** on the test set.

## Approach
- Random Forest Regressor inside a scikit-learn Pipeline
- Preprocessing with ColumnTransformer: imputation, scaling, one-hot encoding
- IQR-based outlier handling

## Stack
Python · scikit-learn · pandas · NumPy
