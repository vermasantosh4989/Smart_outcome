
# Student Performance Prediction using Ensemble Machine Learning

## Project Overview

This project focuses on predicting **students' course completion status (Classification)** and **final score (Regression)** using various **Ensemble Machine Learning algorithms**. The objective is to compare different ensemble techniques and identify the best-performing model for both classification and regression tasks.

The project follows a complete Machine Learning pipeline, including data preprocessing, exploratory analysis, model development, evaluation, and comparison.

---

# Objectives

- Perform data preprocessing and feature engineering.
- Predict course completion status using classification models.
- Predict students' final scores using regression models.
- Implement multiple ensemble learning techniques.
- Compare ensemble methods using standard evaluation metrics.
- Identify the best-performing ensemble model.

---

# Dataset

The dataset contains information related to students' learning activities and academic performance.

### Target Variables

### Classification
- `completion_status`

### Regression
- `final_score`

---

# Project Workflow

## Part A – Data Preprocessing

- Load dataset
- Check dataset information
- Check missing values
- Fill missing values using SimpleImputer
- Remove duplicate records
- Detect and remove outliers
- Encode categorical variables
- Feature selection
- Feature scaling
- Save cleaned dataset

---

## Part B – Exploratory Data Analysis (EDA)

- Dataset summary
- Statistical analysis
- Correlation matrix
- Distribution plots
- Box plots
- Count plots
- Pair plots
- Feature importance analysis

---

## Part C – Bagging

### Classification

- Decision Tree Classifier
- Bagging Classifier

### Regression

- Decision Tree Regressor
- Bagging Regressor

Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Confusion Matrix
- ROC Curve
- MAE
- RMSE
- R² Score

---

## Part D – AdaBoost

### Classification

- AdaBoost Classifier

### Regression

- AdaBoost Regressor

Analysis

- Sequential learning of weak learners
- Performance comparison

---

## Part E – Gradient Boosting

### Classification

- Gradient Boosting Classifier

### Regression

- Gradient Boosting Regressor

Analysis

- Learning Rate
- Number of Estimators

---

## Part F – LightGBM

### Classification

- LightGBM Classifier

### Regression

- LightGBM Regressor

Analysis

- Training efficiency
- Performance comparison
- Feature Importance

---

## Part G – XGBoost

### Classification

- XGBoost Classifier

### Regression

- XGBoost Regressor

Analysis

- Performance comparison
- Robustness analysis
- Feature Importance

---

## Part H – Voting & Stacking

### Voting Classifier

- Hard Voting
- Soft Voting

### Stacking

- Stacking Classifier
- Stacking Regressor

Meta Learners

- Logistic Regression
- Linear Regression

---

# Machine Learning Algorithms

## Classification

- Decision Tree
- Bagging Classifier
- AdaBoost Classifier
- Gradient Boosting Classifier
- LightGBM Classifier
- XGBoost Classifier
- Voting Classifier
- Stacking Classifier

---

## Regression

- Decision Tree Regressor
- Bagging Regressor
- AdaBoost Regressor
- Gradient Boosting Regressor
- LightGBM Regressor
- XGBoost Regressor
- Stacking Regressor

---

# Libraries Used

- pandas
- numpy
- matplotlib
- scikit-learn
- lightgbm
- xgboost

---


# Results

The ensemble models were evaluated using multiple classification and regression metrics.

The final comparison includes:

- Decision Tree
- Bagging
- AdaBoost
- Gradient Boosting
- LightGBM
- XGBoost
- Voting
- Stacking

The best model is selected based on:

### Classification

- Highest Accuracy
- Highest Precision
- Highest Recall
- Highest F1 Score
- Highest ROC-AUC

### Regression

- Lowest MAE
- Lowest RMSE
- Highest R² Score

---

# Future Improvements

- Hyperparameter tuning using GridSearchCV or RandomizedSearchCV.
- Cross-validation for more robust evaluation.
- Feature selection using advanced methods.
- Deep Learning models for performance comparison.
- Model deployment using Flask, FastAPI, or Streamlit.

---

# Conclusion

This project demonstrates the implementation and comparison of multiple ensemble learning techniques for both classification and regression tasks. By evaluating Bagging, AdaBoost, Gradient Boosting, LightGBM, XGBoost, Voting, and Stacking models, the project identifies the most effective approach for predicting student course completion status and final scores. The complete workflow—from data preprocessing to model evaluation—provides a practical example of building robust machine learning solutions for educational data analysis.

---


Machine Learning Project – Ensemble Learning Techniques