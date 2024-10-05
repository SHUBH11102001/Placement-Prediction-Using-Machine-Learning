
# Placement Prediction using Machine Learning 

This project implements various Machine Learning (ML) algorithms to predict student placements based on past student data. The project evaluates different ML techniques and compares their performance in forecasting placements, providing insights for better decision-making in academic environments.

## Table of Contents
- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Key Features](#key-features)
- [Technologies Used](#technologies-used)
- [Models and Results](#models-and-results)
- [Conclusions](#conclusions)

## Introduction
This project explores the use of ML to predict placements of students in engineering institutes. It utilizes past student academic and extracurricular data to build predictive models. These models help forecast optimal placements and provide educators with insights for guiding students toward successful career paths.

## Project Structure
The repository includes the following key components:
1. **Data Collection and Preprocessing**: Includes the code for data preprocessing, such as handling null values, one-hot encoding of categorical variables, and data scaling.
2. **Model Development**: Implements various ML models, including Logistic Regression, Naive Bayes, Random Forest, XGBoost, and more.
3. **Model Evaluation**: Performance comparison of all models based on accuracy, precision, recall, and F1 scores.
4. **Visualization**: Graphical representations of data distributions, model accuracy, and correlation heatmaps.

## Key Features
- Exploratory Data Analysis (EDA)
- Comparison of multiple ML models
- One-hot encoding for categorical features
- Hyperparameter tuning using GridSearchCV
- Data visualization for insights
- Model performance evaluation

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- XGBoost

## Models and Results
The following models were implemented and evaluated:
1. **Logistic Regression**: Accuracy - 78.3%
2. **K-Nearest Neighbors**: Accuracy - 83.3%
3. **Naive Bayes**: Accuracy - 79.5%
4. **Random Forest**: Accuracy - 88.1%
5. **Support Vector Classifier**: Accuracy - 84.7%
6. **XGBoost**: Accuracy - 89.1%

Additionally, ensemble models such as Naive Bayes-Decision Trees hybrid and Logistic Regression-Naive Bayes fusion were tested but did not outperform simpler models like Random Forest and XGBoost.

## Conclusions
XGBoost, Random Forest, and SVC achieved the highest accuracy in predicting student placements.


