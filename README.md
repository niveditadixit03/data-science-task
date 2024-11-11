# Dataset Exploration and Model Development

## 1. Dataset Exploration

**Objective:**  
Explore the popular Iris dataset to understand the basic characteristics of the data.

**Steps:**
- **Load Dataset**: Load the Iris dataset from `sklearn.datasets`.
- **Display First Five Rows**: View the initial rows to get an understanding of the dataset structure.
- **Dataset Shape**: Display the shape of the dataset to know the number of samples and features.
- **Summary Statistics**: Calculate and display key summary statistics, including:
  - Mean
  - Standard deviation
  - Minimum and maximum values for each feature

**Outcome:**  
A clear overview of the dataset’s features, their values, and statistical measures to understand data distribution.


## 2. Data Splitting

**Objective:**  
Split the Iris dataset into training and testing sets for effective model training and evaluation.

**Steps:**
- **Data Splitting**: Use an 80-20 split to divide the data.
  - 80% for training and 20% for testing.
- **Sample Counts**: Display the number of samples in each split to confirm the division.

**Outcome:**  
Separate training and testing datasets to ensure that the model is evaluated on unseen data, which aids in validating model performance.


## 3. Linear Regression

**Objective:**  
Develop a linear regression model using a dataset containing `YearsExperience` and `Salary` features.

**Steps:**
- **Model Training**: Fit a linear regression model to predict `Salary` based on `YearsExperience`.
- **Model Evaluation**: Evaluate the model’s performance on the test set using the Mean Squared Error (MSE) metric.

**Outcome:**  
A trained linear regression model with an evaluation of prediction accuracy based on MSE, indicating the model’s prediction error on the test set.



