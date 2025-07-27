# 📊 Customer Churn Prediction in Telco Data  
_A Data Science Project using Logistic Regression, Random Forest, and Gradient Boosting_

## 📁 Project Overview
This project focuses on predicting customer churn using a real-world telecommunications dataset. The goal is to build a classification model that can identify customers who are likely to stop subscribing, and understand what factors influence this decision.

## 🧠 Objectives
- Explore the dataset and understand churn patterns.
- Clean and preprocess data including missing values and outliers.
- Build and evaluate classification models.
- Interpret feature importance to provide business insights.

## 🛠️ Technical Skills Demonstrated
- **Data Cleaning**: handling missing values, outliers, duplicates, and inconsistent formats.
- **EDA (Exploratory Data Analysis)**: univariate & bivariate analysis using `matplotlib` and `seaborn`.
- **Feature Engineering**: label encoding for categorical variables.
- **Modeling**:
  - Logistic Regression
  - Random Forest Classifier
  - Gradient Boosting Classifier
- **Model Evaluation**: accuracy, precision, recall, F1-score, ROC-AUC, confusion matrix.
- **Model Interpretation**: feature importance using logistic regression coefficients.

## 🧪 Models Performance Comparison

| Model               | Accuracy (Train) | Accuracy (Test) | Notes                |
|---------------------|------------------|-----------------|----------------------|
| Logistic Regression | 80%              | 79%             | ✅ Best (stable)     |
| Random Forest       | 100%             | 78%             | ❌ Overfitting       |
| Gradient Boosting   | 82%              | 79%             | ⚠️ Slight overfit    |

## 🔍 Key Findings
- Most influential features for churn prediction (based on Logistic Regression):
  - `PhoneService`
  - `SeniorCitizen`
  - `PaperlessBilling`
  - `StreamingTV`
  - `InternetService`

## 📦 Tools Used
- Python (Jupyter Notebook)
- Pandas, NumPy
- scikit-learn
- Matplotlib, Seaborn

## ✨ Author
Created by Nurliana  
As part of the **DQLab Data Science Learning Program**

## 📁 File 
