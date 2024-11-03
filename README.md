# Fraudulent Transaction Identification System

## Overview

This project aims to develop a system to identify fraudulent transactions in financial data using Python and Machine Learning techniques, specifically Logistic Regression. The system analyzes a dataset of transaction data to identify patterns associated with fraudulent activities, trains a logistic regression model, and visualizes the results to provide insights into fraud detection.

## Libraries Used

- **NumPy**
- **pandas**
- **seaborn**
- **matplotlib**
- **scikit-learn**
- **imbalanced-learn**

## Dataset

The dataset used for this project is a transaction dataset sourced from Kaggle, containing various features related to financial transactions. The target variable indicates whether a transaction is fraudulent (1) or not (0).

### Data Exploration

- Checking for missing values.
- Summary statistics to understand data distribution.
- Visualization of class distribution to assess the balance of the dataset.
- Correlation heatmap to identify relationships between features.

## Model Development

1. **Data Preprocessing**:

   - Separating features and the target variable.
   - Applying SMOTE to handle class imbalance.
   - Splitting the data into training and testing sets.

2. **Model Training**:

   - Training a Logistic Regression model on the training data.
   - Making predictions on the test data.

3. **Model Evaluation**:
   - Calculating accuracy and generating a classification report.
   - Visualizing the confusion matrix to assess model performance.

## Visualization

- Feature importance analysis to identify key features affecting fraudulent transactions.
- Confusion matrix visualization for performance assessment.
