# Day 23 - Machine Learning Project: Car Price Prediction (Part II)

## Date

Day 23 of ML Training

## Objective

To complete the Car Price Prediction project by evaluating models, building an ensemble model, and deploying the solution as an interactive Streamlit web application.

## Topics Covered

### 1. Model Evaluation

* R² Score
* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* Five-Fold Cross Validation

### 2. Ensemble Learning

* Combined Random Forest and XGBoost using a Voting Regressor
* Compared ensemble performance with individual models

### 3. Model Validation

* Tested Log Transformation of the target variable
* Evaluated removal of low-priced vehicles
* Selected only improvements that enhanced model performance

### 4. Model Deployment

Developed an interactive Streamlit application featuring:

* Vehicle details input form
* Dynamic Manufacturer and Model selection
* Real-time price prediction
* Prediction error margin
* Display of encoded feature vector

### 5. Model Persistence

* Saved the preprocessing pipeline
* Saved the trained model using Joblib
* Reused the same pipeline for deployment

### 6. Project Documentation

* Documented the complete workflow in a Jupyter Notebook
* Ensured reproducibility of all preprocessing and modeling steps
* Published the project on GitHub

## Activities Performed

* Compared multiple regression models.
* Built an ensemble prediction model.
* Performed cross-validation.
* Developed a Streamlit web application.
* Integrated the trained model with the deployment interface.
* Published the completed project to GitHub.

## Key Learnings

* Model comparison helps identify the best-performing algorithm.
* Cross-validation provides a more reliable estimate of model performance.
* Streamlit enables rapid deployment of Machine Learning models.
* Using the same preprocessing pipeline during deployment ensures prediction consistency.
* Every preprocessing and modeling decision should be validated experimentally rather than assumed.

## Project Repository

**GitHub:** https://github.com/singhanmolpreet/car_price_prediction

## Summary

Day 23 concluded the Car Price Prediction project by evaluating regression models, developing an ensemble model, and deploying the final solution using Streamlit. The project demonstrated the complete Machine Learning workflow—from preprocessing and feature engineering to model evaluation and real-world deployment.
