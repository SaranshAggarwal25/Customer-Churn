# Customer Churn Prediction Project

This project focuses on predicting customer churn using various machine learning techniques. The dataset used for this project is stored in "customer_churn.csv".
![Data Head](/screenshots/data.head.png)

### Table of Contents

1. Data Visualization
2. Linear Regression
3. Logistic Regression
4. Decision Tree
5. Random Forest
6. Model Evaluation

## Data Visualization

### Bar-Plot for InternetService

![InternetService Distribution](/screenshots/distribution_of_internet_service.png)

- X-axis: Categories of Internet Service
- Y-axis: Count of Categories
- Title: Distribution of Internet Service
- Color: Orange

### Histogram for Tenure

![Tenure Distribution](screenshots/tenure_distribution.png)

- Bins: 30
- Color: Green
- Title: Distribution of Tenure

### Scatter-Plot for MonthlyCharges vs Tenure

![MonthlyCharges vs Tenure](screenshots/monthlycharges_vs_tenure.png)

- X-axis: Tenure of customer
- Y-axis: Monthly Charges of customer
- Title: Tenure vs Monthly Charges
- Color: Brown

### Box-Plot for Contract vs Tenure

![Contract vs Tenure](screenshots/contract_vs_tenure.png)

- Y-axis: Tenure
- X-axis: Contract
- Title: Contract vs Tenure

## Linear Regression

### Simple Linear Model

- Divided the dataset into a train and test set (70:30 ratio).
- Built the model on the train set, predicted values on the test set.
- Calculated root mean square error: 28.79

## Logistic Regression

### Simple Logistic Model

- Divided the dataset into a train and test set (65:35 ratio).
- Built the model on the train set, predicted values on the test set.
- Confusion matrix: [[1770, 0], [692, 0]]
- Accuracy: 0.72

### Multiple Logistic Model

- Divided the dataset into a train and test set (80:20 ratio).
- Built the model on the train set, predicted values on the test set.
- Confusion matrix: [[938, 95], [215, 159]]
- Accuracy: 0.78

## Decision Tree

### Decision Tree Model

- Divided the dataset into a train and test set (80:20 ratio).
- Built the decision tree model on the train set, predicted values on the test set.
- Confusion matrix: [[1005, 48], [292, 62]]
- Accuracy: 0.76

## Random Forest

### Random Forest Model

- Divided the dataset into a train and test set (70:30 ratio).
- Built the random forest model on the train set, predicted values on the test set.
- Confusion matrix: [[1315, 234], [319, 242]]
- Accuracy: 0.74

## Model Evaluation

- Linear Regression Mean Squared Error: 28.79
- Logistic Regression Confusion Matrix: [[1770, 0], [692, 0]]
  - Accuracy: 0.72
- Multiple Logistic Regression Confusion Matrix: [[938, 95], [215, 159]]
  - Accuracy: 0.78
- Decision Tree Confusion Matrix: [[1005, 48], [292, 62]]
  - Accuracy: 0.76
- Random Forest Confusion Matrix: [[1315, 234], [319, 242]]
  - Accuracy: 0.74
