# DVD Rental Duration Prediction

## Overview
This project uses machine learning to predict how many days customers rent DVDs from a rental company.

## Dataset
The dataset, `rental_info.csv`, contains rental details, movie attributes, pricing information, and special features.

## Objective
Build a regression model that predicts DVD rental duration with a test-set MSE of 3 or less.

## Methodology
- Data preprocessing and feature selection
- Feature engineering
- Training and hyperparameter tuning of regression models
- Model evaluation using Mean Squared Error (MSE)

## Results
A tuned Random Forest Regressor achieved:
- **Best features:** `amount`, `amount_2`, `length_2`
- **Best hyperparameters:** `n_estimators=51`, `max_depth=10`
- **Test MSE:** 2.23

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Jupyter Notebook.
