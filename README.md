# Heart Disease Prediction Using Machine Learning

## Overview

This project explores how machine learning can be used to predict the presence of heart disease from patient data.
It uses common health indicators such as age, cholesterol level, blood pressure, and exercise habits to train predictive models that can support early diagnosis and prevention efforts.

## Objectives

• Explore and understand the dataset through analysis and visualization.
• Build and compare classification models to predict heart disease.
• Identify which features are most strongly related to heart disease.
• Evaluate model performance using standard metrics.

## Dataset

**Source:** Kaggle – Heart Disease Prediction Dataset
The dataset contains patient information including age, sex, chest pain type, resting blood pressure, cholesterol, fasting blood sugar, maximum heart rate, and exercise-induced angina.
The target variable indicates whether heart disease is present or absent.

## Methodology

**1. Data preparation:** cleaned and encoded data, handled categorical variables, and normalized numeric features.
**2. Exploratory analysis:** checked correlations and distributions to understand feature relationships.
**3. Model training:** trained two models — Logistic Regression and Random Forest Classifier.
**4. Evaluation:** measured performance with accuracy, precision, recall, and F1 score, and visualized results with confusion matrices.

## Results

| Model               | Accuracy | Precision |  Recall  | F1 Score |
| :------------------ | :------: | :-------: | :------: | :------: |
| Logistic Regression |   ~0.91  |    High   |   High   |   High   |
| Random Forest       |   ~0.87  |  Moderate | Moderate | Moderate |

Logistic Regression achieved the best performance overall, showing that a simple linear model can effectively separate the classes in this dataset.

## Tools and Libraries

Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## Conclusion

The project shows how structured clinical data can be used to build predictive models for heart disease.
The results suggest that even simple algorithms can provide useful insights for healthcare analysis when combined with proper data cleaning, visualization, and evaluation.
Future improvements could include feature engineering, cross-validation, and model tuning for stronger generalization.

