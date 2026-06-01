# Logistic Regression on Housing Dataset

A straightforward machine learning project that demonstrates how to build, train, 
and evaluate a Logistic Regression classifier using a real housing dataset. The 
project predicts the furnishing status of a property based on its physical and 
financial attributes.

## Overview

Logistic Regression is one of the foundational algorithms in machine learning for 
classification tasks. This project walks through the complete workflow — data 
loading, preprocessing, encoding, model training, and evaluation — making it a 
clean reference for anyone learning supervised classification in Python.

## What This Project Does

- Loads a housing dataset and performs exploratory checks for structure and 
  missing values
- Drops rows with missing values and encodes all categorical columns using 
  Label Encoding
- Defines furnishing status as the classification target
- Splits the data into 80% training and 20% testing sets
- Trains a Logistic Regression classifier on the preprocessed data
- Evaluates the model using accuracy score, confusion matrix, and a full 
  classification report
- Visualizes the confusion matrix as a heatmap for clear performance interpretation

## Tech Stack

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn (Logistic Regression, LabelEncoder, train_test_split)

## Dataset

The project uses a housing dataset containing property features such as area, 
number of bedrooms, bathrooms, stories, parking, and various binary amenity 
flags, with furnishing status as the target variable.

## Author

M. Talal Bin Waheed
