**Disease Prediction Machine Learning Models :**
----------------------------------------------------------------------------------
This repository contains two machine learning projects focused on healthcare analytics: predicting cancer severity and stages, and classifying diabetes risk using various supervised learning algorithms.

**1. Cancer Prediction Model :**
----------------------------------------------------------------------------------
This project analyzes a dataset of 50,000 global cancer patients (2015–2024) to predict the Cancer Stage and a Target Severity Score.

Dataset Overview:
-----------------------------
Source: global_cancer_patients_2015_2024.csv

Key Features:
-----------------------------
Age, Genetic Risk, Air Pollution, Alcohol Use, Smoking, Obesity Level, Treatment Cost (USD), and Survival Years.

Target Variables:
-----------------------------
Cancer_Stage: Categorical (Stage 0 to Stage IV).

Target_Severity_Score: 
-----------------------------
Numerical value.

**Models & Performance**
Logistic Regression:
-----------------------------
Used for classifying the cancer stage.
Linear Regression:
-----------------------------
Used to predict the severity score, achieving an accuracy (R²-style) of approximately 99.99% on the test set.

K-Nearest Neighbors (KNN): 
-----------------------------
Implemented for classification tasks.



**2. Diabetes Prediction Model :**
----------------------------------------------------------------------------------
This project utilizes the Pima Indians Diabetes dataset to classify whether a patient has diabetes based on diagnostic measurements.

Dataset Overview:
-----------------------------
Source: YBI Foundation Dataset (Diabetes.csv).

Features:
-----------------------------
Pregnancies, Glucose, Diastolic Blood Pressure, Triceps Skinfold Thickness, Insulin, BMI, Diabetes Pedigree Function (DPF), and Age.

Target Variable:
-----------------------------
diabetes (Binary: 1 for positive, 0 for negative).

**Models & Performance**
Logistic Regression:
-----------------------------
Applied for binary classification.

K-Nearest Neighbors (KNN): 
-----------------------------
Achieved an accuracy of approximately 64.9% on the test set.


scikit-learn: Model training, splitting (train_test_split), and evaluation (accuracy_score, r2_score).

matplotlib: Data visualization.
