# TP1-SistemasdeIA
Machine learning project to predict real estate prices in Buenos Aires
Overview

The goal of this project is to build regression models capable of estimating property prices based on features such as:

location

property type

surface area

number of rooms and bathrooms

The project covers the full machine learning workflow: data cleaning, preprocessing, feature engineering, model training, and evaluation.

Methods

Key techniques used:

Data preprocessing and missing value imputation

Outlier analysis using IQR

One-Hot Encoding for categorical variables

Linear, Ridge, Lasso, and Polynomial Regression models

Hyperparameter tuning with GridSearchCV

Model evaluation using RMSE and R²

Results

The final model achieved approximately:

RMSE: ~75,296 USD

R²: ~0.61

This means the model explains around 61% of the variance in property prices.

Tools & Libraries

Python

Pandas

NumPy

Scikit-learn

Matplotlib / Seaborn

Google Colab
