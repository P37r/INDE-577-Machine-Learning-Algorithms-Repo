# Principal Component Analysis (PCA)

---

## Overview

**Principal Component Analysis (PCA)** is a dimensionality reduction technique used to project high-dimensional data into a lower-dimensional space, while preserving as much variance as possible.

### Mathematical Form

PCA finds orthogonal vectors (principal components) by performing eigen decomposition on the data's covariance matrix:

$$
X_{\text{projected}} = X W
$$

Where:
- $W$ contains the top-k eigenvectors (principal components),
- $X$ is the mean-centered data matrix.

The top components explain the directions of greatest variance.

---

## Objective

**Task:** Reduce the dimensionality of the dataset to visualize clusters and improve performance for other models.

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
- `sklearn`  
- `matplotlib`  
- `seaborn`  