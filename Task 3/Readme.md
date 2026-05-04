Task 3: Customer Churn Prediction (Bank Customers)
Objective

The objective of this project is to predict whether a bank customer is likely to leave the bank (customer churn) using machine learning models.
The project focuses on analyzing customer demographic and banking information to identify factors that influence churn behavior.

Approach
1. Dataset Understanding

The dataset contains 10,000 customer records with features such as:

Credit Score
Geography
Gender
Age
Balance
Number of Products
Credit Card Status
Estimated Salary
Exited (Target Variable)

Target Variable:

0 → Customer Stayed
1 → Customer Left
2. Data Cleaning and Preparation

The following preprocessing steps were performed:

Checked for missing values
Removed unnecessary columns:
1 RowNumber
2 CustomerId
3 Surname

Encoded categorical variables:
1 Label Encoding for Gender
2 One-Hot Encoding for Geography
3 Applied feature scaling using StandardScaler


3. Exploratory Data Analysis (EDA)

Visualizations were created to better understand customer churn patterns:

1 Customer churn distribution
2 Gender vs churn
3 Geography vs churn
4 Age distribution
5 Feature importance graph

4. Model Training

Two machine learning classification models were trained:

1 Logistic Regression
2 Random Forest Classifier

The dataset was split into training and testing sets using an 80-20 ratio.

5. Model Evaluation

Models were evaluated using:

Accuracy
MAE (Mean Absolute Error)
RMSE (Root Mean Squared Error)
Confusion Matrix


Results and Insights

Logistic Regression
Accuracy: 81.1%
MAE: 0.189
RMSE: 0.435
Random Forest
Accuracy: 86.6%
MAE: 0.134
RMSE: 0.366


Key Insights
Random Forest outperformed Logistic Regression in churn prediction.
Age was the most influential feature affecting customer churn.
Estimated Salary, Credit Score, Balance, and Number of Products also had strong impact on churn behavior.
Geography showed some influence, particularly customers from Germany.

Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn


Conclusion

This project demonstrated the complete workflow of a machine learning classification problem, including:

Data preprocessing
Categorical feature encoding
Model training and evaluation
Feature importance analysis

The Random Forest model provided the best overall performance for predicting customer churn.