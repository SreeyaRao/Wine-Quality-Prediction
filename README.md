# Wine Quality Prediction using Machine Learning
Predicting wine quality using supervised machine learning models including Logistic Regression, Support Vector Machine (SVM), and XGBoost.

## Overview

This project develops a machine learning model to classify wine quality based on its physicochemical properties. Using the Wine Quality dataset, the project performs data preprocessing, exploratory data analysis (EDA), feature engineering, and model comparison to predict whether a wine is of **good quality** or **low quality**.

Three machine learning algorithms—Logistic Regression, Support Vector Machine (SVM), and XGBoost—are trained and evaluated, with XGBoost achieving the best overall performance.

---
## Highlights

- Built an end-to-end binary classification pipeline
- Performed data cleaning, feature engineering, and exploratory data analysis
- Compared Logistic Regression, SVM, and XGBoost models
- Achieved **82% test accuracy** with XGBoost
- Evaluated performance using ROC-AUC, Precision, Recall, F1-score, and Confusion Matrix
---
## Features

- Data cleaning and preprocessing
- Missing value imputation
- Exploratory Data Analysis (EDA)
- Feature engineering
- Correlation analysis
- Data normalization using Min-Max Scaling
- Model training and comparison
- Performance evaluation using multiple metrics
- Confusion matrix visualization

---

## Dataset

The project uses the **Wine Quality Dataset**, which contains physicochemical measurements for both red and white wines.

### Features

- Type (Red/White)
- Fixed Acidity
- Volatile Acidity
- Citric Acid
- Residual Sugar
- Chlorides
- Free Sulfur Dioxide
- Total Sulfur Dioxide
- Density
- pH
- Sulphates
- Alcohol

### Target Variable

The original quality score is converted into a binary classification problem:

- **Good Quality (1):** Quality > 5
- **Low Quality (0):** Quality ≤ 5

---

## Project Workflow

### 1. Data Preprocessing

- Loaded the dataset using Pandas
- Checked for missing values
- Replaced missing numerical values using mean imputation
- Converted categorical wine type into numerical values
- Removed highly correlated features
- Created a binary target variable

### 2. Exploratory Data Analysis

- Summary statistics
- Histograms for feature distributions
- Alcohol vs Quality visualization
- Correlation heatmap

### 3. Feature Engineering

- Created binary target variable (`best quality`)
- Removed the original quality column
- Selected relevant features for model training

### 4. Model Training

The following machine learning algorithms were implemented:

- Logistic Regression
- Support Vector Machine (RBF Kernel)
- XGBoost Classifier

### 5. Model Evaluation

Models were evaluated using:

- ROC-AUC Score
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

### Best Model

**XGBoost Classifier**

Performance on the test dataset:

- Accuracy: **82%**
- Precision: **82%**
- Recall: **82%**
- Weighted F1-Score: **82%**

---

