

### Loan Eligibility and Customer Clustering
Introduction:
### This project aims to:
  ### Predict loan eligibility for customers using both XGBoost and RandomForest classification models with GridSearch for hyperparameter tuning.
  ### Group customers into segments using K-Means clustering based on behavioral and financial attributes..
The project showcases two main aspects of customer analysis: predicting loan approval and identifying customer segments TO tailor business strategies..

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
### 1. Loan Eligibility Classification (Classification.ipynb):
Data Preprocessing:
Handle missing values (if any).
Convert categorical variables into numerical format (e.g., Employment_Status).
Split the dataset into features (X) and target variable (y).
Model Building:
Implement both RandomForestClassifier and XGBoostClassifier from the scikit-learn and XGBoost libraries, respectively.
Used GridSearchCV to tune hyperparameters for both models.
Model Evaluation:
Evaluate the model’s performance using metrics like Accuracy.
### 2. Customer Clustering (USERS.ipynb):
Data Preprocessing:
Normalize the numerical data to ensure all features contribute equally to the clustering.
Model Building:
Use the K-Means algorithm to group customers into different clusters.
Use the Elbow method to determine the optimal number of clusters.
Cluster Analysis:
Visualize and analyze the clusters based on key attributes like income, debt, and credit score.

#### This project demonstrates how machine learning models like RandomForest and XGBoost can be used to predict loan eligibility using GridSearch for hyperparameter tuning. Additionally, customer segmentation is achieved through K-Means clustering, helping businesses gain insights into their customer base for targeted strategies.
