Credit Card Fraud Detection with Logistic Regression
This project uses logistic regression to classify transactions as legitimate or fraudulent, based on the Credit Card Fraud Detection dataset. The model is trained on a balanced subset of the dataset to accurately predict fraudulent transactions. Additionally, an interactive widget allows you to upload a CSV file and predict each transaction's legitimacy.

Table of Contents
Overview
Dataset
Project Structure
Installation
Usage
Results
License
Overview
The primary goal of this project is to develop a logistic regression model that can effectively detect fraudulent transactions. The model's performance is evaluated with accuracy metrics, a confusion matrix, and classification reports. To handle the imbalanced data, undersampling of legitimate transactions is applied.

Dataset
Source: The dataset is from the Credit Card Fraud Detection dataset.
Features:
Time, Amount, and anonymized principal components V1 through V28
Class is the target, where 0 indicates a legitimate transaction and 1 indicates a fraudulent one.
Project Structure
creditcard.csv: The original dataset (add this locally, or ensure it’s downloaded if used in notebooks).
fraud_detection.py: Python script containing the main code for model training, evaluation, and prediction.
README.md: This file.
Installation
To run this project, you'll need to have Python and the following libraries installed:

pip install numpy pandas seaborn matplotlib scikit-learn ipywidgets
Usage
Model Training and Evaluation:

Run the code to load the data, preprocess it, train the logistic regression model, and display metrics.
Predict on Uploaded File:

Use the widget to upload a CSV file for prediction.
The uploaded file should have columns matching the features (V1 to V28, Time, and Amount) to predict legitimate or fraudulent transactions.
Visualization:

View class distributions, amount distributions, and a correlation heatmap.
Confusion matrix and classification report are displayed after model training.
Results
The logistic regression model's performance is evaluated by:

Accuracy: Measures the correct predictions.
Confusion Matrix: Visualizes true vs. predicted values.
Classification Report: Provides precision, recall, and F1-score for both classes.
License
This project is licensed under the MIT License.
