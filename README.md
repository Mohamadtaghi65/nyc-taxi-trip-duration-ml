# NYC Taxi Trip Duration Prediction 🚕

![Python](https://img.shields.io/badge/Python-3.x-blue)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-orange)
![Regression](https://img.shields.io/badge/Task-Regression-green)
![Dataset](https://img.shields.io/badge/Dataset-NYC%20Taxi-yellow)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## Overview
This repository contains an end-to-end machine learning project to predict the duration of NYC taxi trips using spatio-temporal data.

The goal of this project is not only to train a model, but to demonstrate a complete ML workflow including data cleaning, feature engineering, modeling, and evaluation.

## Dataset
Source: Kaggle – NYC Taxi Trip Duration  
Target variable: `trip_duration` (seconds)

## Project Workflow
1. Data loading and inspection  
2. Data cleaning and preprocessing  
3. Exploratory Data Analysis (EDA)  
4. Feature engineering (time-based and distance-based features)  
5. Train/Test split  
6. Model training (baseline → advanced models)  
7. Evaluation using MAE and RMSE  

## Feature Engineering Highlights
- Pickup hour, day of week, and weekend indicators  
- Haversine distance between pickup and dropoff locations  
- Optional rush-hour indicators  
- Log transformation of the target variable  

## Models Used
- Linear Regression  
- Random Forest Regressor  
- Gradient Boosting / XGBoost (if applicable)

## Evaluation Metrics
- Mean Absolute Error (MAE)  
- Root Mean Squared Error (RMSE)

## Results
The models show significant improvement over baseline after feature engineering, highlighting the importance of temporal and spatial features in trip duration prediction.

## Notebook
The full implementation and analysis can be found in the Kaggle notebook:

(https://www.kaggle.com/code/mohammadtaghipro/linear-regression-random-forest-xgboost-nyc-taxi)

## Next Improvements
- Cross-validation  
- Hyperparameter tuning  
- Better handling of outliers  
- Transition to a production-style pipeline  

## Author
Mohammadtaghi Rezaei Hosseinabadi
