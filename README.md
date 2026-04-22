# HeartDisease-Classification-MachineLearning-

❤️ Heart Disease Prediction using Machine Learning

This project focuses on building a predictive model to determine whether a patient is likely to have heart disease based on medical attributes. The model leverages multiple machine learning algorithms, with a primary focus on Logistic Regression for binary classification.

📌 Project Overview

The dataset consists of various health-related features such as age, sex, chest pain type, cholesterol levels, blood pressure, and more. Using these features, the model predicts the presence (1) or absence (0) of heart disease.

The workflow includes:

Data preprocessing and cleaning
Exploratory Data Analysis (EDA) with visualizations
Feature engineering using dummy variables
Model building from scratch (Logistic Regression)
Implementation using Scikit-learn
Performance comparison across multiple algorithms
⚙️ Algorithms Used
Logistic Regression (Manual + Scikit-learn)
K-Nearest Neighbors (KNN)
Support Vector Machine (SVM)
Naive Bayes
Decision Tree
📊 Model Performance
Logistic Regression Accuracy: 86.89%
KNN Accuracy: 88.52% (best)
SVM Accuracy: 86.89%
Naive Bayes Accuracy: 86.89%
Decision Tree Accuracy: ~80%
🔍 Key Features of the Project
Custom implementation of Logistic Regression (including sigmoid, cost function, and gradient descent)
Visualization of relationships between features and target variable
Comparison of multiple classification models
Hyperparameter tuning (K value in KNN)
📁 Dataset Information

The dataset includes the following features:

Age, Sex
Chest Pain Type (cp)
Resting Blood Pressure (trestbps)
Cholesterol (chol)
Fasting Blood Sugar (fbs)
Maximum Heart Rate (thalach)
Exercise Induced Angina (exang)
ST Depression (oldpeak)
Number of Major Vessels (ca)
Thalassemia (thal)
Target (Heart Disease: Yes/No)
