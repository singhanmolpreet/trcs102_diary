# Day 22 - Machine Learning Project: Car Price Prediction

## Date

Day 22 of ML Training

## Objective

To begin the development of a complete Machine Learning project for predicting used car prices by performing data preprocessing, feature engineering, and training multiple regression models.

## Project Overview

Developed a Car Price Prediction System capable of estimating the resale value of used cars based on vehicle attributes such as manufacturer, model, production year, mileage, engine specifications, fuel type, transmission, and other features.

## Topics Covered

### 1. Data Preprocessing

* Handling missing and placeholder values
* Removing duplicate records
* Cleaning inconsistent data
* Preventing data leakage by performing preprocessing only on the training set

### 2. Feature Engineering

* Extracting Engine Size from Engine Volume
* Creating a Turbo indicator feature
* Converting Mileage into numerical format
* Preparing categorical and numerical features for modeling

### 3. Outlier Handling

* Detecting outliers using the Interquartile Range (IQR) method
* Removing outliers from training data only

### 4. Categorical Encoding

Applied different encoding techniques based on feature characteristics:

* One-Hot Encoding
* Ordinal Encoding
* Binary Encoding
* Frequency Encoding
* Target (CatBoost) Encoding

### 5. Missing Value Imputation

* K-Nearest Neighbors (KNN) Imputation for missing Levy values

### 6. Model Development

* Built a baseline Random Forest Regressor
* Trained and tuned Random Forest
* Trained and tuned XGBoost Regressor

## Activities Performed

* Cleaned and preprocessed the dataset.
* Engineered meaningful features.
* Applied multiple encoding techniques.
* Built preprocessing pipelines.
* Trained multiple regression models.

## Key Learnings

* Proper preprocessing significantly improves model performance.
* Preventing data leakage is essential for obtaining reliable evaluation results.
* Different categorical features require different encoding techniques.
* Feature engineering can increase the predictive power of Machine Learning models.

## Summary

Day 22 focused on preparing the dataset for Machine Learning by performing preprocessing, feature engineering, encoding, and training multiple regression models. These steps established the foundation for building a reliable car price prediction system.
