📊 Customer Churn Prediction (Task 3)

📌 Objective  
The goal of this task is to predict whether a bank customer is likely to leave the bank using machine learning classification models.

⚙️ Approach

- Performed data cleaning and preprocessing
- Removed unnecessary columns:
  - RowNumber
  - CustomerId
  - Surname
- Encoded categorical features:
  - Label Encoding for Gender
  - One-Hot Encoding for Geography
- Applied feature scaling using StandardScaler
- Conducted Exploratory Data Analysis (EDA) using:
  - Count plots
  - Histograms
  - Correlation visualization
- Trained two classification models:
  - Logistic Regression
  - Random Forest Classifier
- Evaluated models using:
  - Accuracy
  - Confusion Matrix
  - MAE
  - RMSE
- Analyzed feature importance using Random Forest


📈 Results & Insights

- Random Forest achieved ~86.6% accuracy, outperforming Logistic Regression (~81.1%).
- Random Forest produced lower MAE and RMSE, making it the better model for churn prediction.
- Age was the most influential feature affecting customer churn.
- Other important features included:
  - Estimated Salary
  - Credit Score
  - Balance
  - Number of Products
- Geography also showed impact on churn behavior, especially customers from Germany.