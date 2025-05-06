# K-Nearest Neighbors (KNN)

---

## Overview

**K-Nearest Neighbors (KNN)** is a simple, instance-based learning method used for both classification and regression. It assumes that data points with similar features exist in close proximity to each other.

In classification, the model predicts the class of a new observation based on the **majority class** among its **k nearest neighbors** in the training set.

### How It Works

1. Choose a value for $k$ (the number of neighbors).
2. Compute the distance (commonly Euclidean) from the new data point to all points in the training set.
3. Identify the $k$ points closest to the new input.
4. Assign the class most common among those neighbors.

KNN is **non-parametric** and doesn't make any assumptions about the underlying data distribution.

---

## Objective

**Task:** Predict whether or not a person has diabetes based on their health data using a distance-based method.

---

## Dataset Features

- Gender  
- Age  
- Race  
- Hypertension  
- Heart Disease  
- Smoking  
- BMI  
- HbA1c Level  
- Blood Glucose Level  

---

## Tools and Libraries

- `pandas`  
- `SMOTE`  
- `sklearn`  
- `matplotlib`  
- `seaborn`  

---