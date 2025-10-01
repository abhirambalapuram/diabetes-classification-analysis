# Pima Diabetes Prediction

This project explores the Pima Indians Diabetes dataset to identify key risk factors and build predictive models for diabetes onset. It demonstrates the full workflow of a data analyst: data cleaning, EDA, modeling, and interpretation of results.

## Objective

Perform exploratory analysis to understand relationships between health metrics and diabetes outcomes.

Train classification models to predict whether a patient is likely to have diabetes.

Evaluate and compare model performance.

Highlight the most important features influencing predictions.

## Dataset

Source: https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database

Rows: 768 female patients of Pima Indian heritage (aged 21+).

Features (8):

Pregnancies

Glucose

BloodPressure

SkinThickness

Insulin

BMI

DiabetesPedigreeFunction

Age

Target: Outcome (0 = No Diabetes, 1 = Diabetes)

## Methods

### 1. Data Cleaning

Replaced biologically impossible zero values in Glucose, BloodPressure, SkinThickness, Insulin, and BMI with median values.

### 2. Exploratory Data Analysis

Outcome distribution

Correlation heatmap

Feature distributions and group comparisons

### 3. Modeling

Logistic Regression (baseline, with scaling)

Random Forest (ensemble, for non-linear patterns)

### 4. Evaluation Metrics

Accuracy, Precision, Recall, F1-Score, ROC AUC

Confusion Matrix and ROC Curve

### 5. Interpretability

Logistic Regression coefficients

Random Forest feature importances

## Results (example run)

Logistic Regression: Accuracy ≈ 0.78, ROC AUC ≈ 0.81

Random Forest: Accuracy ≈ 0.83, ROC AUC ≈ 0.86

Key predictors: Glucose level, BMI, Age, and Diabetes Pedigree Function

## Tech Stack

Python, pandas, NumPy, scikit-learn, matplotlib, seaborn
