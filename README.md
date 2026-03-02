# Spaceship Titanic – ML Classification

## Overview
Binary classification problem to predict whether a passenger was transported.

## Workflow
- Data cleaning and EDA
- One-hot encoding using `pd.get_dummies`
- Stratified train–validation split
- Feature scaling with `StandardScaler`
- Logistic Regression model
- Evaluation using Accuracy and F1-score

## Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Jupyter Notebook

## Notes
- Validation data is derived from training data
- Test dataset is used only for final prediction

## Model Performance
- Accuracy: **79.18%**
- F1-score: **79.52%**
