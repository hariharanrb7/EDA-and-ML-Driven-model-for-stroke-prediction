# 🧠 Stroke Prediction using EDA and Machine Learning

This repository contains an end-to-end machine learning pipeline for predicting the likelihood of a stroke in patients using clinical and demographic data. The project focuses on Exploratory Data Analysis (EDA) and model development to generate actionable insights and accurate predictions.

## 📌 Table of Contents

Project Overview

Dataset

EDA and Insights

Preprocessing Steps

Models Used

Performance Evaluation

Results

Installation & Usage

Project Structure

Future Work

Author


## 🔍 Project Overview

Stroke is a leading cause of death and long-term disability. Early prediction using patient data can help in preventive measures. This project uses statistical analysis, visual exploration, and machine learning to:

Understand key features influencing stroke

Train predictive models

Evaluate their performance

📊 Dataset
Source: Kaggle


Features:

Demographics: age, gender, ever_married, etc.

Health conditions: hypertension, heart_disease, avg_glucose_level, etc.

Target variable: stroke

## 📈 EDA and Insights

EDA was conducted using:

Univariate and bivariate analysis

Visualizations using seaborn and matplotlib

Correlation heatmaps to detect relationships

## Key insights:

Higher stroke risk in patients with hypertension and heart disease

Age and average glucose level are strong indicators

Imbalanced dataset (fewer stroke cases)

## 🔧 Preprocessing Steps

Handling missing values

Encoding categorical features (gender, smoking_status, etc.)

Feature scaling using StandardScaler

Addressing class imbalance with SMOTE (Synthetic Minority Oversampling Technique)

## 🤖 Models Used

Logistic Regression

Random Forest Classifier

K-Nearest Neighbors (KNN)

XGBoost

## Evaluation metrics used:

Accuracy

Precision

Recall

F1-score

ROC-AUC curve

## 📊 Performance Evaluation

Emphasis on Recall to minimize false negatives (important in medical applications)

Random Forest and XGBoost performed best in balancing precision and recall

## ✅ Results

| Model               | Accuracy | Recall | F1-Score |
| ------------------- | -------- | ------ | -------- |
| Logistic Regression | \~83%    | 0.79   | 0.80     |
| Random Forest       | \~88%    | 0.84   | 0.85     |
| XGBoost             | \~89%    | 0.86   | 0.87     |

## 🚀 Future Work

Deploy model using Streamlit or Flask

Integrate model into a medical dashboard

Experiment with deep learning techniques (e.g., MLPs)

Feature engineering with domain expertise

## 👤 Author
## Hariharan R.B
