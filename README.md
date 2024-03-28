# Module_13_Challenge

# Spam Detector

## Overview
This project aims to build a spam detector using machine learning algorithms. The dataset used for this project is sourced from the UCI Machine Learning Library and contains various features related to email messages, such as word frequencies and character counts. The goal is to train and evaluate two models - Logistic Regression and Random Forest Classifier - to predict whether an email is spam or not.

## Workflow
1. Data Import: The dataset is imported using the Pandas library. The resulting DataFrame is displayed to confirm the successful import.

2. Model Performance Prediction: Before creating and fitting the models, a prediction is made on which model is expected to perform better. The justification for the prediction is provided in a markdown cell.

3. Data Split: The data is split into training and testing sets using the train_test_split function from the sklearn.model_selection module.

4. Feature Scaling: The features data is scaled using the StandardScaler from the sklearn.preprocessing module. Only the training data (X_train) and testing data (X_test) are scaled.

5. Logistic Regression Model: A Logistic Regression model is created, fitted to the scaled training data, and evaluated using the testing data. The accuracy score is printed.

6. Random Forest Classifier Model: A Random Forest Classifier model is created, fitted to the scaled training data, and evaluated using the testing data. The accuracy score is printed.

7. Model Evaluation: The performance of both models is compared, and the model with the higher accuracy score is identified. The results are documented in a markdown cell.

## Findings

Based on the evaluation, the Random Forest Classifier model performed better than the Logistic Regression model. The Random Forest Classifier achieved a higher accuracy score, indicating its effectiveness in predicting spam emails. This finding aligns with the initial prediction made in the project.

## Resources
OSU Bootcamp Starter Files

Github Copilot
