# Breast Cancer Classification using Logistic Regression

## Overview
This project builds a supervised machine learning model to classify tumors as **malignant** or **benign** using Logistic Regression.

## Dataset
- Samples: 569
- Features: 30 (mean, standard error, worst measurements)
- Target: Binary classification (Malignant / Benign)

## Workflow
1. Data Cleaning & Preprocessing  
   - Handled missing values  
   - Feature scaling (standardization)  

2. Feature Engineering  
   - Grouped features (mean, SE, worst)  
   - Correlation analysis to reduce redundancy  

3. Model Training  
   - Logistic Regression model  

4. Evaluation  
   - Accuracy: ~94–97%  
   - Metrics: Precision, Recall, F1-score  
   - High recall (>95%) for malignant cases  

## Tech Stack
- Python  
- NumPy, Pandas  
- Scikit-learn  
- Matplotlib, Seaborn  

## Results
The model performs strongly in detecting malignant tumors, prioritizing high recall to minimize false negatives.
