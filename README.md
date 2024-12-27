# House Price Prediction using XGBoost 🏠

## Overview
This project implements a machine learning model to predict house prices using the Boston Housing Dataset. The model utilizes XGBoost regression to achieve high accuracy in price predictions based on various housing features.

## Project Highlights ✨
- Achieved 92.6% R² score on test data
- Mean Absolute Error of 1.99
- Uses the renowned Boston Housing Dataset
- Implements XGBoost Regressor for accurate predictions

## Dependencies 📚
```
pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
```

## Dataset Description 📊
The Boston Housing Dataset contains information about various features of houses in Boston. The dataset includes 506 samples with 13 feature variables and 1 target variable (PRICE).

### Features:
- CRIM: Crime rate
- ZN: Proportion of residential land zoned
- INDUS: Proportion of non-retail business acres
- CHAS: Charles River dummy variable
- NOX: Nitric oxide concentration
- RM: Average number of rooms
- AGE: Proportion of owner-occupied units built prior to 1940
- DIS: Weighted distances to employment centers
- RAD: Index of accessibility to radial highways
- TAX: Property tax rate
- PTRATIO: Pupil-teacher ratio
- B: Proportion of Black residents
- LSTAT: Percentage of lower status population

### Target Variable:
- PRICE: Median value of owner-occupied homes in $1000s

## Data Quality 🔍
- No missing values in the dataset
- No duplicate entries
- Well-balanced feature distributions

## Model Implementation 🛠️
1. Data Preprocessing:
   - Loading and initial data exploration
   - Feature-target separation
   - Train-test split (80-20 ratio)

2. Model Training:
   - XGBoost Regressor with default parameters
   - Training on 80% of the data

3. Model Evaluation:
   - R² Score: 0.926 (92.6% accuracy)
   - Mean Absolute Error: 1.99

## Feature Importance 📈
Based on the correlation analysis, the following features showed strong correlation with house prices:
- RM (Number of rooms): Strong positive correlation
- LSTAT (Lower status population): Strong negative correlation
- PTRATIO (Pupil-teacher ratio): Negative correlation



## Future Improvements 🚀
1. Hyperparameter tuning using GridSearchCV
2. Feature engineering to create more meaningful variables
3. Implementation of cross-validation
4. Ensemble with other models for better performance
5. Development of a web interface for predictions

