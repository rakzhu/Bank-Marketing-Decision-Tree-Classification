# Bank-Marketing-Decision-Tree-Classification

# Description 

Machine Learning project using Decision Tree & GridSearchCV to predict customer subscription behavior in a bank marketing campaign.

# Bank Marketing Campaign Prediction using Decision Tree
# Project Overview

This project focuses on predicting whether a customer will subscribe to a term deposit based on a bank's marketing campaign data.
The dataset contains customer demographic details, financial information, and campaign-related attributes.
The goal of this project is to:
Clean and preprocess the dataset
Engineer meaningful features
Train a Decision Tree classifier
Optimize the model using GridSearchCV
Evaluate performance using classification metrics

# Technologies Used

Python
Pandas
Matplotlib
Scikit-learn
DecisionTreeClassifier
GridSearchCV
Confusion Matrix
Classification Report

# Dataset

The dataset contains features such as:
Age
Job
Marital Status
Education
Balance
Housing Loan
Personal Loan
Campaign details
Target variable (y) – whether the client subscribed

# Data Preprocessing Steps

Converted categorical “yes/no” columns into boolean values
Created a new feature balance_class using custom categorization
Removed irrelevant columns
Encoded categorical variables using OrdinalEncoder
Split dataset into train and test sets using stratified sampling

# Model Building

Two models were trained:
Basic Decision Tree
Optimized Decision Tree using GridSearchCV
Hyperparameters tuned:
max_depth
criterion (gini / entropy)
min_samples_split
min_samples_leaf
Cross-validation (cv=10) was used for better model stability.

# Model Evaluation

Model performance was evaluated using:
Confusion Matrix
Precision
Recall
F1-score
Cross-validation
