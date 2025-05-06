# DBSCAN (Density-Based Spatial Clustering)

---

## Overview

**DBSCAN (Density-Based Spatial Clustering of Applications with Noise)** is an unsupervised learning algorithm that forms clusters based on the density of data points. Unlike K-Means, it does not require specifying the number of clusters.

### Key Concepts

- **ε (epsilon):** Radius to search for neighboring points.
- **minPts:** Minimum number of points to form a dense region.

Points are classified as:
- **Core points:** Have at least `minPts` neighbors within ε.
- **Border points:** Not core, but within ε of a core point.
- **Noise points:** Neither core nor border.

---

## Objective

**Task:** Cluster individuals with similar health profiles using DBSCAN to uncover natural groupings in the dataset.

---

## Dataset Features

- PCA-reduced features (e.g., 2D or 3D)
- Derived from:  
  - Age  
  - BMI  
  - HbA1c  
  - Glucose  

---

## Tools and Libraries

- `pandas`  
- `sklearn`  
- `matplotlib`  
- `seaborn`  

---
