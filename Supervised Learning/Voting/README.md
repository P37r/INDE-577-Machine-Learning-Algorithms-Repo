## Part 2: Diabetes Prediction Using Voting Ensemble

### Overview

**Voting** is an ensemble machine learning method where multiple classifiers are trained on the same dataset, and their predictions are aggregated to produce a final output.

There are two main types of voting:

- **Hard Voting**: The class predicted by the majority of classifiers is selected.  
- **Soft Voting**: The average of predicted class probabilities is computed, and the class with the highest average probability is selected.

The key advantage is that different models (e.g., logistic regression, decision trees, naive Bayes) can be used together, combining their strengths and reducing individual weaknesses.

### Objective

**Task:** Predict whether a person has diabetes using an ensemble of models and aggregate their outputs via voting.

### Dataset Features

The dataset includes the following health-related features:

- Gender  
- Age  
- Race  
- Hypertension  
- Heart Disease  
- Smoking Status  
- BMI  
- HbA1c Level  
- Blood Glucose Level  

### Tools and Libraries

- `pandas` – Data preprocessing and manipulation  
- `SMOTE` – Handling class imbalance  
- `sklearn` – Machine learning models and ensemble voting  
- `matplotlib` – Visualization  
- `seaborn` – Data plotting and exploration  