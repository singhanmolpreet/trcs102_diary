# Day 13 - Categorical Data Encoding

## Date

Day 13 of ML Training

## Objective

To understand the importance of encoding categorical data and learn different encoding techniques used in Machine Learning.

## Topics Covered

### 1. Introduction to Encoding

* What is categorical data?
* Why encoding is required
* Types of categorical variables:

  * Nominal
  * Ordinal

### 2. One-Hot Encoding

* Concept of One-Hot Encoding
* Creating binary columns for each category
* Suitable for nominal categorical variables
* Advantages and limitations

### 3. Label Encoding

* Assigning a unique integer to each category
* When to use Label Encoding
* Limitations for nominal data

### 4. Ordinal Encoding

* Encoding categories based on a predefined order
* Suitable for ordinal categorical variables
* Defining category order before encoding

## Activities Performed

* Applied One-Hot Encoding to nominal features.
* Converted categorical labels into numerical values using Label Encoding.
* Encoded ordered categories using Ordinal Encoding.
* Compared the use cases of different encoding techniques.

## Key Learnings

* Machine Learning algorithms require numerical input; categorical data must be encoded before model training.
* One-Hot Encoding is preferred for nominal data because it does not introduce an artificial order.
* Label Encoding assigns unique integers to categories but may imply an unintended ranking.
* Ordinal Encoding is appropriate only when the categories have a meaningful order.

## Summary

Day 13 focused on converting categorical variables into numerical representations using One-Hot Encoding, Label Encoding, and Ordinal Encoding. Choosing the appropriate encoding technique is an essential step in data preprocessing for Machine Learning.
