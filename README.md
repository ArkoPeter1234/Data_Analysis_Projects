# Data_Analysis_Projects
This repository contains various data analysis projects, scripts, and notebooks. It showcases techniques in data cleaning, exploration, visualization, and modeling. The goal is to extract insights, build meaningful reports, and support decision-making with data-driven solutions.
Overview
This project demonstrates an end-to-end machine learning classification workflow using synthetic data.
It covers model training, evaluation, interpretation, and feature importance comparison across multiple models:

Logistic Regression

Random Forest

XGBoost

Additionally, it leverages SHAP (SHapley Additive exPlanations) for explainable AI and visualizes feature importances across models.

Key Steps
Generate a synthetic dataset with random features and binary targets.

Split the dataset into training and testing sets.

Train three machine learning models.

Evaluate models using performance metrics: Accuracy, Precision, Recall, F1-Score, and ROC-AUC.

Visualize the confusion matrix for Random Forest.

Interpret feature importances using SHAP for XGBoost.

Compare feature importances between Random Forest and XGBoost models.

Requirements
Python 3.x

Libraries:

pandas

numpy

scikit-learn

matplotlib

seaborn

xgboost

shap


Visual Outputs
Confusion Matrix for Random Forest

SHAP Summary Plot for XGBoost

Feature Importance Bar Chart (Random Forest vs XGBoost)

Purpose
Practice model evaluation techniques.

Understand model interpretability using SHAP.

Compare classical and ensemble machine learning models.

Demonstrate a complete and explainable machine learning workflow.

