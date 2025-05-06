
# Neural Networks

---

## Overview

**Neural Networks** are composed of layers of interconnected neurons. Each neuron computes a weighted sum of inputs and passes the result through a nonlinear activation function. By stacking layers and applying backpropagation, neural networks can learn complex, non-linear patterns in data.

### Layer Computation

$$
a^{(l)} = \sigma(W^{(l)} a^{(l-1)} + b^{(l)})
$$

where:
- $\sigma$ is the activation function (e.g., ReLU, sigmoid),
- $W^{(l)}$ and $b^{(l)}$ are weights and biases at layer $$l$$,
- $a^{(0)} = x$ is the input.

---

## Objective

**Task:** Train a feedforward neural network to classify whether or not a person has diabetes.

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

---
