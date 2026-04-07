🏷️ Project Title

Loan Approval Prediction using Decision Tree Classification with Model Comparison

📌 Overview

This project focuses on predicting whether a loan will be approved using a Decision Tree Classifier and comparing its performance with Logistic Regression.

The goal is to understand model behavior, overfitting, and the importance of model selection.

🎯 Objectives
Build a Decision Tree Classification model
Handle missing values and preprocess data
Perform hyperparameter tuning
Evaluate using classification metrics
Compare with Logistic Regression
📊 Dataset Description

The dataset contains applicant details such as:

Gender, Married, Dependents
Applicant & Coapplicant Income
Loan Amount & Term
Credit History
Property Area

🎯 Target: Loan_Status (Approved / Rejected)

⚙️ Methodology
1. Data Preprocessing
Handled missing values using mode & median
Dropped unnecessary columns
Applied one-hot encoding
2. Model Building
Decision Tree Classifier implemented
3. Hyperparameter Tuning
Used GridSearchCV
Tuned parameters:
max_depth
min_samples_split
min_samples_leaf
criterion
4. Model Evaluation
Accuracy
Precision, Recall, F1-score
Confusion Matrix
📊 Results
🔹 Decision Tree (After Tuning)
Training Accuracy: 0.82
Testing Accuracy: 0.82
🔹 Logistic Regression
Accuracy: 0.83
⚖️ Model Comparison
Logistic Regression slightly outperformed Decision Tree
Decision Tree showed overfitting initially but improved after tuning
Dataset exhibited patterns better captured by a linear model
🧠 Key Learnings
Model selection depends on data nature
Decision Trees require tuning to avoid overfitting
Evaluation metrics beyond accuracy are important
Simpler models can perform better in structured datasets
📌 Conclusion

Logistic Regression proved to be the more suitable model for this dataset due to its stability and slightly higher accuracy, while Decision Tree provided flexibility but required tuning to achieve similar performance.

🚀 Future Work
Apply Random Forest
Try Gradient Boosting
Improve feature engineering
