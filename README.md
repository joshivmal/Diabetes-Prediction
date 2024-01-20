
# Diabetes Prediction Using Random Forest, Logistic Regression, and K-Nearest Neighbors

Diabetes Prediction Using Random Forest, Logistic Regression, and K-Nearest Neighbors


## Overview
This repository contains Python code for predicting diabetes using machine learning classifiers, including Random Forest, Logistic Regression, and K-Nearest Neighbors. The project employs popular libraries like NumPy, Pandas, Matplotlib, and scikit-learn for implementing and evaluating the classifiers.


    
## Table of contents
Introduction
Installation
Usage
Dataset
Exploratory Data Analysis
Classifiers
Model Evaluation
Hyperparameter Tuning
Final Model
Model Deployment
## Features

- Introduction

- Usage
- Dataset
- Exploratory Data Analysis
- Classifiers
- Model Evaluation
- Hyperparameter Tuning
- Final Model
- Model Deployment
## Introduction
Diabetes is a prevalent chronic condition, and predictive models play a crucial role in identifying individuals at risk. This project utilizes Random Forest, Logistic Regression, and K-Nearest Neighbors classifiers to predict the likelihood of diabetes based on relevant features.
## Installation
Clone the repository:

```bash
git clone https://github.com/your-username/diabetes-prediction.git
cd diabetes-prediction
```
Install the required dependencies:

```bash
pip install -r requirements.txt

```


## Dataset
The dataset used for this project is sourced from Dataset Source. Ensure that you have the dataset file (Healthcare-Diabetes.csv) in the data directory.

## Features
- Feature 1: Glucose
- Feature 2: BloodPressure
- Feature 3: SkinThickness
- Feature 4: Insulin
- Feature 5: BMI
- Feature 6: DiabetesPedigreeFunction
- Feature 7: Age
## Target
Outcome: Diabetes (1 if positive, 0 if negative)
## Exploratory Data Analysis

The exploratory data analysis (EDA) section includes:

- Loading the dataset
- Dropping unnecessary columns (e.g., 'Pregnancies', 'Id')
- Describing the dataset
- Checking for missing values
- Correlation matrix visualization

## Classifiers

The following classifiers are implemented in the project:

- Random Forest Classifier
- Logistic Regression
- K-Nearest Neighbors Classifier

## Model Evaluation

The models are evaluated using standard metrics, including precision, recall, F1 score, ROC curve, and confusion matrix.

## Hyperparameter Tuning
A grid search is performed to find the optimal hyperparameters for the Random Forest Classifier.

## Final Model
The final Random Forest Classifier is trained with the optimal hyperparameters obtained from the grid search.

## Model Deployment
The final model is saved using joblib and can be deployed for making predictions on new data.

## Sample Prediction
A sample input array is provided, and the saved model is loaded to make a prediction.
