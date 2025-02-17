# Disease Prediction using Machine Learning

## Overview
This project focuses on predicting Dry Eye Disease using machine learning techniques. It involves data preprocessing, feature scaling, oversampling, and training multiple classification models to evaluate their performance.

## Dataset
The dataset contains various features related to patient health and habits, including:
- **Demographic information** (e.g., gender)
- **Lifestyle factors** (e.g., caffeine consumption, screen time before bed)
- **Medical conditions** (e.g., sleep disorders, ongoing medication)
- **Symptoms** (e.g., eye strain, redness, irritation)

## Preprocessing Steps
1. **Data Cleaning & Transformation**  
   - Convert categorical values to numerical format  
   - Split blood pressure into systolic and diastolic values  
   - Remove unnecessary columns  

2. **Feature Scaling & Oversampling**  
   - Standardization using `StandardScaler`  
   - Handling class imbalance with `RandomOverSampler`  

## Machine Learning Models Used
The following classification models were trained and evaluated:
- **K-Nearest Neighbors (KNN)**
- **Naive Bayes**
- **Logistic Regression**
- **Support Vector Machine (SVM)**
- **Random Forest**
- **Decision Tree**

## Evaluation
Each model's performance was assessed using:
- **Accuracy**
- **Classification Report (Precision, Recall, F1-Score)**
- **Comparison of Model Results**