# Diabetes Prediction Using Decision Tree

## Overview

This project implements a **Decision Tree** classifier to predict whether or not a person has diabetes based on various health indicators.

A Decision Tree is a supervised machine learning algorithm used for classification tasks. It works by learning decision rules from labeled training data and applying those rules to unseen data to classify it. These decision rules allow for interpretability; however, complex trees may become harder to understand.

## Objective

**Task:** Predict whether a person has diabetes using demographic and clinical health data.

## Dataset Features

The dataset includes the following features:

- Gender  
- Age  
- Race  
- Hypertension (Yes/No)  
- Heart Disease (Yes/No)  
- Smoking Status  
- BMI (Body Mass Index)  
- HbA1c Level (Glycated Hemoglobin)  
- Blood Glucose Level  

## Tools and Libraries

The following Python libraries are used:

- `pandas` – For data manipulation  
- `SMOTE` – For balancing the dataset using synthetic over-sampling  
- `sklearn` – For model building, training, and evaluation  
- `matplotlib` – For data visualization and plotting

## Instructions

1. Load and preprocess the dataset (clean missing values, encode categorical variables, etc.).
2. Handle class imbalance using SMOTE.
3. Split the dataset into training and test sets.
4. Train a Decision Tree classifier on the training data.
5. Evaluate the model on the test set using metrics like accuracy, precision, and recall.
6. Visualize the Decision Tree to understand how the model makes decisions.

## Notes

- Decision Trees are easy to interpret when shallow but can become complex and less understandable as depth increases.
- Use pruning and parameter tuning to avoid overfitting and improve generalization.
