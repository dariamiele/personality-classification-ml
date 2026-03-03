# Personality Classification – Machine Learning Project

## Overview
This project implements a binary classifier to predict whether a person is Extroverted (1) or Introverted (0) based on behavioral and social features.

A complete machine learning pipeline was developed including preprocessing, class imbalance handling, and hyperparameter optimization.

## Methodology
- Missing value imputation
- Feature encoding and standardization (ColumnTransformer)
- RandomOverSampler for class imbalance
- Support Vector Classifier (SVC)
- Nested cross-validation
- Hyperparameter tuning with RandomizedSearchCV

## Results
Test set performance:
- F1-score: 0.925  
- Accuracy: 0.924  
- AUC: 0.923  

The model demonstrates strong generalization and stable validation performance.

## Repository Structure
- `notebook.ipynb`: Full project implementation
- `requirements.txt`: Project dependencies

## How to Run
Install dependencies and run the notebook locally.
