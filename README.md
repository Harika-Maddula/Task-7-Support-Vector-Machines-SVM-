Objective

The objective of this task is to implement Support Vector Machine (SVM) algorithms for both linear and non-linear classification problems. The task demonstrates how SVM models classify binary data using different kernel functions and evaluates performance using cross-validation and hyperparameter tuning.

Tools and Technologies Used
Python Programming Language
NumPy — Numerical Computations
Matplotlib — Data Visualization
Scikit-learn — Machine Learning Model Implementation
Google Colab — Cloud Execution Environment
 Dataset Used
Breast Cancer Dataset
The dataset is a built-in dataset available in Scikit-learn and is commonly used for binary classification tasks.
Dataset Information
Total Samples : 569
Features : 30 Numerical Features
Target Classes :

 Task Workflow / Methodology
1. Data Loading

The dataset is loaded using Scikit-learn's dataset module.

2️. Data Preprocessing

Features and labels separated.

Dataset split into Training and Testing sets.

Standardization performed using StandardScaler.

3️. Model Training

Two SVM models were trained:
Linear Kernel SVM
Used for linear decision boundaries.
RBF Kernel SVM
Used for non-linear classification problems.

 Hyperparameter Tuning
Grid Search Cross Validation was used to find the best parameters:
C (Regularization Parameter)
Gamma (Kernel Co-efficient)
GridSearchCV performs automated tuning using 5-fold cross validation.
 Model Evaluation Metrics


