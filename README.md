# Boston-House-Price-Prediction
Supervised ML regression using XGBoost on Boston Housing dataset

## Project Overview
This project focuses on predicting median house prices in different towns of Boston using supervised machine learning techniques.  
The objective is to analyze how socio-economic, environmental, and housing-related factors influence property prices and to build a regression model for estimation.

---

## Problem Statement
Housing prices depend on multiple interrelated factors such as:
- Crime rate  
- Accessibility to highways  
- Pollution levels  
- Education quality  
- Neighborhood socio-economic status  

The goal of this project is to:
1. Understand key drivers of housing prices  
2. Perform exploratory data analysis (EDA)  
3. Build and evaluate regression models  

---

## Dataset
- Source: Boston Housing Dataset  
- Records: 506  
- Features: 13 input variables  
- Target variable: `MEDV` (Median house value in $1000s)

---

## Exploratory Data Analysis
Key insights from EDA:
- Strong positive correlation between number of rooms (`RM`) and house prices  
- Strong negative correlation between lower-status population percentage (`LSTAT`) and house prices  
- Target variable shows right-skewness withTFand capping at the upper limit (MEDV = 50)

---

## Models Used
- Random Forest Regressor  
- XGBoost Regressor (best-performing)

---

## Model Performance
- **R² Score:** ~0.9
- **RMSE:** 2.4
