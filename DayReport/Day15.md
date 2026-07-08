# Day 15 - Outlier Handling and Train-Test Split

## Date

Day 15 of ML Training

## Objective

To understand how to identify and handle outliers in a dataset and learn the importance of splitting data into training and testing sets before building Machine Learning models.

## Topics Covered

### 1. Outliers

* What are outliers?
* Causes of outliers
* Impact of outliers on Machine Learning models
* When outlier handling is necessary

### 2. Interquartile Range (IQR) Method

* Understanding Quartiles (Q1, Q2, Q3)
* Calculating the Interquartile Range (IQR)
* Detecting outliers using lower and upper bounds
* Removing or capping outliers using the IQR method

### 3. Z-Score Method

* Understanding the Z-Score
* Measuring how far a data point is from the mean
* Identifying outliers using a threshold (commonly ±3)
* Suitable for approximately normally distributed data

### 4. Train-Test Split

* Purpose of splitting the dataset
* Training set vs Testing set
* Common split ratios (80:20 and 70:30)
* Importance of random sampling
* Using `random_state` for reproducibility
* Using `stratify` for classification datasets

## Activities Performed

* Detected outliers using the IQR method.
* Identified outliers using the Z-Score technique.
* Compared the effectiveness of both methods.
* Split the dataset into training and testing sets using `train_test_split()`.
* Explored the use of `random_state` and `stratify`.

## Key Learnings

* Outliers can significantly affect model performance and should be handled appropriately.
* The IQR method is effective for skewed distributions, while the Z-Score method works best for normally distributed data.
* Splitting the dataset before model training helps evaluate the model on unseen data.
* Using `random_state` ensures reproducible results, and `stratify` preserves the class distribution in classification problems.

## Summary

Day 15 focused on identifying and handling outliers using the **IQR** and **Z-Score** methods, followed by learning how to split a dataset into training and testing sets. These preprocessing techniques are essential for building reliable and unbiased Machine Learning models.
