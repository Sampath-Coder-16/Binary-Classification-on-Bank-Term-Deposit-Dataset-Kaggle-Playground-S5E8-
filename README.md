Binary-Classification-on-Bank-Term-Deposit-Dataset-Kaggle-Playground-S5E8-
Complete ML pipeline for bank marketing classification (Kaggle S5E8): data cleaning, one-hot encoding, model training with cross-validation, ROC evaluation, and ensemble-ready outputs for practice and showcasing applied machine learning skills.
Project Overview: Binary Classification on Bank Term Deposit Dataset (Kaggle Playground S5E8)

This project is my solution to the Kaggle Playground Series – Season 5, Episode 8 competition.
The challenge is to build machine learning models that predict whether a bank client will subscribe to a term deposit.
The dataset combines demographic, financial, and campaign-related features, and the task is framed as a binary classification problem.

Key Highlights
Objective: Predict the probability of a client subscribing to a bank term deposit.
Dataset: Training set with 750,000 rows, test set with 250,000 rows, 16 features (mixed numerical and categorical).

Target Variable: y (0 = No, 1 = Yes).
Evaluation Metric: ROC AUC (Area Under the Receiver Operating Characteristic Curve).

Workflow Steps
Data exploration and preprocessing
Checked feature distributions and missing values.
Applied StandardScaler for numerical features and OneHotEncoder for categorical features.

Model training and cross-validation
Models: Logistic Regression, Random Forest, LightGBM, SVM, KNN, and Naive Bayes.
Used Stratified 5-Fold Cross Validation for reliable ROC AUC scoring.

Predictions and submissions
Generated probability predictions for the test set.
Saved individual submission files for each model.

Visualization and evaluation
Plotted ROC curves and probability distributions to compare model performance.
Combined submission file
Created combined_submission.csv with predictions from all models for potential ensembling.

Outcome
This project provides a full end-to-end machine learning pipeline including data processing, model comparison, evaluation, and competition-ready submissions.
It highlights the importance of cross-validation, ROC AUC as a metric, and the potential benefits of ensembling.

📂 Repository Link:
GitHub Repo
