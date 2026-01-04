# Housing Price Prediction using OLS Regression

## Project Overview
This is a practice project to predict housing prices using
Ordinary Least Squares (OLS) regression with Statsmodels.

## Steps Performed
- Data loading and preprocessing
- Feature engineering
- Exploratory Data Analysis (EDA)
- Multicollinearity check using VIF
- Baseline OLS model
- Outlier treatment using IQR
- Model evaluation and validation

## Model Used
- OLS Regression (Statsmodels)

## Results
- Train R²: 0.62
- Test R²: 0.59

## Key Insights
- Median income is the strongest predictor of house price
- Outlier handling improved model performance
- Model generalizes well on unseen data

## Tools & Libraries
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Statsmodels
- Scikit-learn


## Dataset: California Housing Dataset

Columns:

MedInc – Median income in the area

HouseAge – Median house age

AveRooms – Average rooms per household

AveBedrms – Average bedrooms per household

Population – Area population

AveOccup – Average occupants per household

Houseprice – Median house value (scaled)
