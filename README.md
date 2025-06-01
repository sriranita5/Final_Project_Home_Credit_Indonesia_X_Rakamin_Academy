# Final Project Home Credit Indonesia X Rakamin Academy

📊 Credit Scoring Project – Home Credit Indonesia
This project aims to build a robust and interpretable credit scoring model using supervised machine learning to predict the likelihood of loan default among applicants, based on Home Credit Indonesia's historical data.

🧠 Problem Statement
Credit risk is one of the most critical challenges in lending businesses. This project develops a model that predicts whether a customer is likely to default on a loan (TARGET = 1) or not, enabling smarter lending decisions and risk management.

📁 Dataset Description
Dataset used:
- application_train.csv – contains historical loan application data with TARGET (default label).
- application_test.csv – similar structure, used for prediction (no TARGET).
  
Each row represents a single loan application, with over 300K observations and 120 features, including:
- Demographic data (e.g., age, gender, education)
- Financial info (income, credit amount)
- Employment status
- Property and asset ownership

🛠️ Project Workflow
1. Data Cleaning & Preprocessing
- Handle missing values
- Feature selection
- Encode categorical variables (LabelEncoder)
- Outlier removal using Z-score
2. Feature Scaling
- Standardization using StandardScaler
3. Class Imbalance Handling
- Synthetic Minority Over-sampling Technique (SMOTE)
4. Model Training
- Logistic Regression
- Random Forest Classifier
5. Model Evaluation
- Accuracy, Precision, Recall, F1-Score
- Confusion Matrix
- ROC-AUC Curve
6. Business Recommendations
- Segmented credit products
- Risk-based offer personalization
