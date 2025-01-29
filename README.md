Project Overview

This project aims to classify breast cancer cases as malignant or benign using a machine learning model. The dataset used is the Breast Cancer Wisconsin Dataset from Scikit-Learn. The goal is to build a classification model, evaluate its performance, and document the findings.

Dataset


Source: Scikit-Learn's load_breast_cancer() dataset

Features: 30 numerical features describing characteristics of cell nuclei

Target Classes:

0: Malignant

1: Benign


Machine Learning Model


Model Used: Random Forest Classifier

Preprocessing:

Standardized features using StandardScaler

Split dataset into training (80%) and testing (20%)

Evaluation Metrics:

Accuracy Score

Classification Report

Confusion Matrix



Results & Insights

The Random Forest Classifier achieved an accuracy of over 95% on the test set.

The confusion matrix shows that the model correctly classified most cases with very few misclassifications.

The classification report provides precision, recall, and F1-score metrics, confirming the model’s strong performance


