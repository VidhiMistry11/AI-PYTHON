# AI-PYTHON
Loan Approval Prediction System

Our machine learning project that predicts whether a loan application will be approved based on applicant details such as income, 
employment status, education, dependents, credit history, and more.

Objective:
To build a predictive model that helps financial institutions determine loan approval outcomes using historical loan data.
The model analyzes multiple applicant factors and outputs Approved / Not Approved.

Dataset
The dataset used is publicly available on Kaggle:
🔗 https://www.kaggle.com/datasets/architsharma01/loan-approval-prediction-dataset

It contains:
  Income details
  Education status
  Employment status
  Loan amount
  Credit history
Target variable: Loan Status

* PROJECT WORKFLOW 
1. Data Collection
Dataset imported from Kaggle and loaded into the notebook.

2. Data Preprocessing
  Handling missing values
  Removing duplicates
  Encoding categorical variables
  Scaling numerical features
  Outlier treatment

3. Exploratory Data Analysis (EDA)
Visualizations include:
  Box plots
  Distribution plots
These help understand patterns affecting loan approval.

4. Model Training
Tested classifiers:
  Logistic Regression
  K-Nearest Neighbors
Libraries used:
  scikit-learn
  pandas
  numpy
  matplotlib

5. Model Evaluation Metrics used:
  Accuracy
  Confusion Matrix
  Classification Report
Logistic Regression performed best and was selected as the final model.

6. Conclusion
Logistic Regression achieved the highest accuracy and delivered the best performance for predicting loan approval outcomes.
It handles multiple variables effectively and produces interpretable results, making it suitable for real-world deployments.
