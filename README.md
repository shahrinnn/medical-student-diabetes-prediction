# Medical Student Diabetes Prediction

Machine learning project developed as part of our **CSE422: Artificial Intelligence** academic group project. The project explores medical student health and lifestyle data to predict diabetes and identify patterns using supervised and unsupervised machine learning techniques.

## Project Overview

The dataset contains medical student health information including demographic, physical, and lifestyle-related attributes. The project focuses on preprocessing the data, exploring relationships between features, training multiple classification models, evaluating their performance, and applying clustering techniques.

## Machine Learning Workflow

- Data cleaning and preprocessing
- Handling missing values
- Categorical feature encoding
- Feature scaling
- Exploratory Data Analysis (EDA)
- Train-test split (70% training / 30% testing)
- Classification model training
- Model performance evaluation
- ROC-AUC analysis
- K-Means clustering

## Models Implemented

### Logistic Regression
Used as a baseline classification model for predicting diabetes.

### Decision Tree
Used to capture non-linear relationships between health and lifestyle features.

### Neural Network
Implemented to explore more complex relationships within the dataset.

### K-Means Clustering
Applied as an unsupervised learning technique to identify underlying groups within the medical student data.

## Model Evaluation

The classification models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC Curve
- AUC Score

An important observation from the analysis was the effect of **class imbalance**. High accuracy alone did not necessarily indicate strong diabetes detection performance, making precision, recall, F1-score, and ROC-AUC important for comparing the models.

## Key Result

The Decision Tree achieved approximately **85.98% accuracy**, with **32.7% precision** and **37.92% recall** for the diabetes classification task.

The analysis also demonstrated why model performance should not be judged using accuracy alone when working with imbalanced medical datasets.

## Dataset

The dataset contains approximately **200,000 records and 13 attributes**, including health and lifestyle-related information, with **Diabetes** used as the target variable.

## Tech Stack

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Project Files

- `Group19_23101044_22299127.ipynb` — Complete machine learning implementation
- `medical_students_dataset...` — Dataset used for analysis and model training
- `Group19_23101044_22299127.docx` — Academic project report

## Academic Project

**Course:** CSE422 — Artificial Intelligence  
**Project Type:** Academic Group Project

This repository contains the implementation and documentation of our course project. The work included data preprocessing, exploratory analysis, classification, model evaluation, and clustering.

## Key Learning Outcomes

Through this project, we gained practical experience in:

- Building an end-to-end machine learning workflow
- Preparing real-world data for ML models
- Training and comparing classification algorithms
- Understanding the impact of class imbalance
- Evaluating models beyond accuracy
- Applying supervised and unsupervised machine learning techniques
