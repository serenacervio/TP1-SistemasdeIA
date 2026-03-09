# TP1-SistemasdeIA
Machine learning project to predict real estate prices in Buenos Aires
## Overview

The goal of this project is to build regression models capable of estimating property prices based on features such as:

- location
- property type
- surface area
- number of rooms
- number of bathrooms

The project covers the full machine learning workflow: data cleaning, preprocessing, feature engineering, model training, and evaluation.

## Methods

Key techniques used:

- Data preprocessing and missing value imputation
- Outlier analysis using the IQR method
- One-Hot Encoding for categorical variables
- Linear, Ridge, Lasso, and Polynomial Regression
- Hyperparameter tuning using GridSearchCV
- Model evaluation using RMSE and R²

## Results

Final model performance:

- **RMSE:** ~75,296 USD
- **R²:** ~0.61

The model explains approximately **61% of the variance in property prices**.

## Tools & Libraries

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Google Colab


