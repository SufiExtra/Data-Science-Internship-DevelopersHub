📊 Customer Churn Prediction (Task 3)

📌 Objective  
The goal of this task is to predict whether a bank customer is likely to leave the bank using machine learning classification models.

⚙️ Approach

1. Performed data cleaning and preprocessing
2. Removed unnecessary columns:
  1. RowNumber
  2. CustomerId
  3. Surname
3. Encoded categorical features:
  1. Label Encoding for Gender
  2. One-Hot Encoding for Geography
4. Applied feature scaling using StandardScaler
5. Conducted Exploratory Data Analysis (EDA) using:
  1. Count plots
  2. Histograms
6. Trained two classification models:
  1. Logistic Regression
  2. Random Forest Classifier
7. Evaluated models using:
  1. Accuracy
  2. Confusion Matrix
  3. MAE
  4. RMSE
8. Analyzed feature importance using Random Forest


📈 Results & Insights

1. Random Forest achieved ~86.6% accuracy, outperforming Logistic Regression (~81.1%).
2. Random Forest produced lower MAE and RMSE, making it the better model for churn prediction.
3. Age was the most influential feature affecting customer churn.
4. Other important features included:
  1. Estimated Salary
  2. Credit Score
  3. Balance
  4. Number of Products
5. Geography also showed impact on churn behavior, especially customers from Germany.