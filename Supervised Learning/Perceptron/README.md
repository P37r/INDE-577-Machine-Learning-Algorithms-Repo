# Perceptron

---

## Overview

The **Perceptron** is a linear binary classifier and one of the earliest types of artificial neural networks. It predicts outcomes based on a **weighted combination** of inputs passed through an activation function.

### Mathematical Form

$$
\hat{y} = 
\begin{cases}
1 & \text{if } \mathbf{w} \cdot \mathbf{x} + b > 0 \\
0 & \text{otherwise}
\end{cases}
$$

The perceptron updates weights using the perceptron learning rule:

$$
\mathbf{w} \leftarrow \mathbf{w} + \alpha(y - \hat{y})\mathbf{x}
$$

where:
- $\alpha$ is the learning rate,
- $y$ is the true label,
- $\hat{y}$ is the prediction.

---

## Objective

**Task:** Train a linear classifier to determine whether or not an individual has diabetes using their health indicators.

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