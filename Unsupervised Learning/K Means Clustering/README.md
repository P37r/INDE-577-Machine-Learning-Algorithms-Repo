## K-Means Clustering

### Overview

**K-Means clustering** is one of the most straightforward and widely used unsupervised machine learning algorithms. The core idea is to group data points together based on their similarity — it's essentially clustering by proximity.

Here’s the general process:
1. Choose the number of clusters you want, $K$.
2. Place $K$ initial cluster centers (often chosen randomly).
3. Assign each data point to the nearest cluster based on distance (typically Euclidean distance).
4. Recalculate the cluster centers by averaging all data points assigned to that cluster.
5. Repeat steps 3 and 4 until the cluster centers no longer move significantly or a max iteration count is reached.

This process minimizes the **in-cluster sum of squared errors (SSE)**, giving us compact clusters.

### Objective

**Task:** Use unsupervised learning to identify natural groupings in the data. First, apply **PCA (Principal Component Analysis)** to reduce the data to two dimensions, then perform K-Means clustering on the reduced feature space.

### Dataset Features

The dataset contains health-related attributes:

- Gender  
- Age  
- Race  
- Hypertension  
- Heart Disease  
- Smoking  
- BMI  
- HbA1c Level  
- Blood Glucose Level  

### Tools and Libraries

- `pandas` – Data preprocessing  
- `sklearn` – PCA and K-Means algorithm  
- `SMOTE` – Balancing the dataset (if applied pre-clustering)  
- `matplotlib` – Visualizing clusters  
- `seaborn` – Enhanced plotting and styling  

---