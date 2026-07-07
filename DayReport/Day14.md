# Day 14 - Feature Scaling and Feature Selection

## Date

Day 14 of ML Training

## Objective

To understand the importance of feature scaling and feature selection in Machine Learning and learn commonly used techniques for preprocessing data.

## Topics Covered

### 1. Feature Scaling

* What is feature scaling?
* Why feature scaling is important
* Difference between normalization and standardization

#### StandardScaler

* Standardizes features by removing the mean and scaling to unit variance.
* Produces data with a mean of 0 and a standard deviation of 1.
* Commonly used with algorithms such as K-Nearest Neighbors (KNN), Support Vector Machines (SVM), Logistic Regression, and Principal Component Analysis (PCA).

#### MinMaxScaler

* Scales features to a fixed range, usually between 0 and 1.
* Preserves the relative distribution of the data.
* Useful when features have different ranges and bounded values are preferred.

### 2. Feature Selection

* Introduction to feature selection
* Importance of selecting relevant features
* Benefits:

  * Reduces model complexity
  * Improves training efficiency
  * Reduces overfitting
  * Enhances model interpretability

#### Sequential Feature Selector (SFS)

* Wrapper-based feature selection technique
* Evaluates feature subsets using a Machine Learning model
* Types of SFS:

  * Forward Selection
  * Backward Selection
* Selects the subset of features that gives the best model performance

## Activities Performed

* Applied `StandardScaler` to standardize numerical features.
* Used `MinMaxScaler` to normalize feature values.
* Compared the effect of different scaling techniques.
* Performed feature selection using Sequential Feature Selector (SFS).
* Identified the most important features for model training.

## Key Learnings

* Feature scaling ensures that numerical features contribute equally during model training.
* StandardScaler is suitable when data follows a normal distribution, while MinMaxScaler is useful when a fixed range is required.
* Feature selection helps remove irrelevant or redundant features, improving model performance and reducing computational cost.
* Sequential Feature Selector systematically identifies the optimal subset of features based on model performance.

## Summary

Day 14 focused on two essential preprocessing techniques: **Feature Scaling** and **Feature Selection**. Scaling improves the performance of distance- and gradient-based algorithms, while feature selection reduces dimensionality by retaining only the most relevant features for building efficient Machine Learning models.
