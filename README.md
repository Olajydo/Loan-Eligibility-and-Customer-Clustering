

### Loan Eligibility and Customer Clustering
Introduction:
###This project aims to:
  ### 1.Predict loan eligibility for customers using a Random Forest classification model.
  ### 2.Group customers into segments using K-Means clustering based on behavioral and financial attributes.
The models are built using provided customer data, and the project demonstrates two key components of customer analysis: loan eligibility prediction and segmentation for personalized strategies.

### Dataset:
### The dataset used for this project contains the following columns:

Customer_ID: Unique ID for each customer.
Credit_Score: A numeric score representing creditworthiness.
Annual_Income: Income of the customer.
Loan_Amount: Amount of loan requested.
Loan_Term: Duration of the loan (in months).
Employment_Status: Employment status (Employed/Unemployed).
Current_Debt: Current amount of debt.
Customer_Segment: Segments used for clustering (output for clustering).
Loan_Approved: Whether the loan was approved or not (target variable for classification).
Methodology:
### 1. Loan Eligibility Classification:
Data Preprocessing:
Handle missing values (if any).
Convert categorical variables into numerical format (e.g., Employment_Status).
Split the dataset into features (X) and target variable (y).
Model Building:
Implement RandomForestClassifier from the scikit-learn library.
Train the model using the training data to predict whether a loan should be approved.
Model Evaluation:
Evaluate the model’s performance using metrics like Accuracy, Precision, Recall, and F1-Score.
### 2. Customer Clustering:
Data Preprocessing:
Normalize the numerical data to ensure all features contribute equally to the clustering.
Model Building:
Use the K-Means algorithm to group customers into different clusters.
Use the Elbow method to determine the optimal number of clusters.
Cluster Analysis:
Visualize and analyze the clusters based on key attributes like income, debt, and credit score.

### This project demonstrates how machine learning techniques can be used to:
  ### Predict loan eligibility using a Random Forest classification model.
  ### Group customers into segments using K-Means clustering for better marketing and risk management strategies.
