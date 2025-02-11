# Heart Disease Prediction using Machine Learning

## Overview

This repository contains a Python-based machine learning project focused on predicting the risk of heart disease in patients. The project utilizes the UCI Heart Disease Dataset and implements various classification models to identify individuals at risk of heart attack.

## Problem Statement

The goal is to build a machine learning model that can accurately classify whether a patient is at risk of heart disease based on a given set of medical data. This project aims to provide a valuable tool for medical research facilities to identify and prioritize patients for further evaluation and preventative care.

## Dataset

The dataset used in this project is the UCI Heart Disease Dataset, available at:
 (https://archive.ics.uci.edu/ml/datasets/Heart+Disease?spm=5176.100239.blogco
 nt54260.8.TRNGoO)

The dataset contains various features related to patient health, including:

*   Age
*   Sex
*   Chest Pain Type
*   Resting Blood Pressure
*   Cholesterol
*   Fasting Blood Sugar
*   Resting ECG
*   Maximum Heart Rate
*   Exercise Induced Angina
*   ST Depression
*   Slope of Peak Exercise ST Segment
*   Number of Major Vessels Colored by Fluoroscopy
*   Thalassemia
*   Target (Heart Disease or No Heart Disease)

## Lab Environment:
 Jupyter Notebook

## Domain:
 Healthcare

 
## Tasks Performed

The following tasks were performed in this project:

1. **Data Analysis:**
 a. Import the dataset
 b. Get information about the dataset (mean, max, min, quartiles etc.)
 c. Find the correlation between all fields


2. **Data Visualization:**
 a. Visualize the number of patients having a heart disease and not having
 a heart disease
 b. Visualize the age and whether a patient has disease or not
 c. Visualize correlation between all features using a heat map

3. **Logistic Regression:**
 a. Build a simple logistic regression model:
 i. Divide the dataset in 70:30 ratio
 ii. Build the model on train set and predict the values on test set
 iii. Build the confusion matrix and get the accuracy score

 4. **Decision Tree:**
 a. Build a decision tree model:
 i. Divide the dataset in 70:30 ratio
 ii. Build the model on train set and predict the values on test set
 iii. Build the confusion matrix and calculate the accuracy
 iv. Visualize the decision tree using the Graphviz package

5. **Random Forest:**
 a. Build a Random Forest model:
 i. Divide the dataset in 70:30 ratio
 ii. Build the model on train set and predict the values on test set
 iii. Build the confusion matrix and calculate the accuracy
 iv. Visualize the model using the Graphviz package


6. **Select the best model**
 a. Print the confusion matrix of all classifiers
 b. Print the classification report of all classifiers
 c. Calculate Recall Precision and F1 score of all the models
 d. Visualize confusion matrix using heatmaps
 e. Select the best model based on the best accuracies
