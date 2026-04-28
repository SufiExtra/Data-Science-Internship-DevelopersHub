📊 Credit Risk Prediction (Task 2)

📌 Objective
The goal of this task is to predict whether a loan applicant is likely to default on a loan using machine learning techniques.

⚙️ Approach
1. Performed data cleaning by handling missing values
2. Conducted EDA using visualizations (histograms, box plots, count plots)
3. Applied data preprocessing:
     1. Dropped irrelevant columns (LoanID)
     2. Encoded categorical variables
4. Scaled features using StandardScaler
5. Trained two models:
     1. Logistic Regression
     2. Decision Tree
6. Evaluated models using accuracy, confusion matrix, and error metrics


📈 Results & Insights
1. Logistic Regression achieved ~88.6% accuracy, outperforming Decision Tree (~80.3%).
2. Logistic Regression had lower error (MAE & RMSE), making it more reliable.
3. Key features influencing prediction include Income, Loan Amount, and Credit Score.