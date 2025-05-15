# Song Popularity ML Analysis

This repository contains a detailed machine learning analysis designed to predict song popularity based on audio features using both regression and classification methods.

## Overview

We implemented and compared the performance of several machine learning models:

- **Decision Trees**
- **Random Forest**
- **Gradient Boosting**

Tasks included:
- Predicting the numeric popularity score (**Regression**).
- Classifying songs into popular/not popular (**Classification**).

##  Methods

- **Data Preprocessing:** Cleaning, feature selection, and data splitting.
- **Model Training:** Decision Trees, Random Forest, Gradient Boosting.
- **Model Evaluation:** RMSE (Regression), Accuracy (Classification).
- **Hyperparameter Tuning:** Using GridSearchCV to optimize Random Forest models.

## Results

**Regression Task:**
- Optimized Random Forest Regressor reduced RMSE to **~16.48**.

**Classification Task:**
- Optimized Random Forest Classifier achieved an accuracy of **95.9%**.

## Conclusions

Random Forest models consistently delivered superior performance, confirming their effectiveness for predictive modeling tasks related to structured audio feature data.
