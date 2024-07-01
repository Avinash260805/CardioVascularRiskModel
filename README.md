Cardiovascular Disease Prediction Model

This repository contains code for a machine learning model that predicts the likelihood of cardiovascular disease based on various health and lifestyle factors. The model utilizes a Random Forest Classifier, a robust algorithm known for its ability to handle complex datasets and provide reliable predictions.

Dataset

The model is trained on a dataset (CVD_cleaned(in).csv) that includes the following features:

General_Health: Self-reported general health status

Checkup: Frequency of health checkups

Exercise: Frequency of exercise

Skin_Cancer: History of skin cancer

Other_Cancer: History of other cancers

Depression: History of depression

Diabetes: History of diabetes

Arthritis: History of arthritis

Sex: Gender of the individual

Age_Category: Age group of the individual

Smoking_History: History of smoking

Height_(cm): Height in centimeters

Weight_(kg): Weight in kilograms

BMI: Body Mass Index (derived from height and weight)

Alcohol_Consumption: Frequency of alcohol consumption

Fruit_Consumption: Frequency of fruit consumption

Green_Vegetables_Consumption: Frequency of green vegetables consumption

FriedPotato_Consumption: Frequency of fried potato consumption

Model Pipeline

The model pipeline includes the following steps:

Data Preprocessing:

Numerical Data: Imputed missing values with the mean and scaled using StandardScaler.
Categorical Data: Imputed missing values with the most frequent value and one-hot encoded.
Model Training:

Utilizes a RandomForestClassifier with 100 estimators and a random state of 0 for reproducibility.

Evaluation:

Model performance is evaluated using accuracy score and a classification report, which includes precision, recall, and F1-score.
Usage

To use the model for prediction:

Ensure Python and necessary libraries (pandas, scikit-learn) are installed.
Load your dataset (CVD_cleaned(in).csv) or prepare new data in the same format.
Run the provided code to preprocess data, train the model, and make predictions.

Requirements
Python 3.x
pandas
scikit-learn
