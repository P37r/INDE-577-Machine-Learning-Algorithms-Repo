## Logistic Regression

### Overview

**Logistic Regression** is a supervised learning algorithm used for binary classification. It models the probability that a given input belongs to a particular class using the sigmoid function:

$$
\sigma(z) = \frac{1}{1 + e^{-z}}
$$

Where:

$$
z = \beta_0 + \beta_1 x_1 + \beta_2 x_2 + \dots + \beta_n x_n
$$

And:

$$
\sigma(z)
$$

gives a value between 0 and 1 — the model’s confidence that the input belongs to the positive class.

During training, logistic regression fits the coefficients $\beta$ to minimize the loss (often binary cross-entropy). When applied to test data:
- If $\sigma(z) > 0.5$, the model predicts class 1.
- Otherwise, it predicts class 0.

### Objective

**Task:** Predict whether or not a person has diabetes using health data. This is a binary classification problem where 1 indicates the presence of diabetes and 0 indicates no diabetes.

### Dataset Features

Same health attributes are used:

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

- `pandas` – Data loading and preprocessing  
- `SMOTE` – Handle class imbalance  
- `sklearn` – Model fitting and evaluation  
- `matplotlib` – Visualization of model performance  
- `seaborn` – Plots and heatmaps for exploration  
