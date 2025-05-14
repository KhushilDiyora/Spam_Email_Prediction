# Spam Email Classification using Logistic Regression

This repository contains a spam email classifier built using Logistic Regression and TF-IDF for feature extraction. The model classifies emails into two categories: spam or ham (non-spam).

# Overview

The project uses a dataset of email messages, which are classified as either spam or ham. The model uses Logistic Regression for classification after transforming the email messages into numerical feature vectors using TF-IDF (Term Frequency-Inverse Document Frequency). The classifier is then evaluated based on its accuracy on both training and test datasets.

# Features

* Data Preprocessing: Handles missing data and encodes labels ('spam' as 0 and 'ham' as 1).

* Text Feature Extraction: Converts text data into numerical vectors using TF-IDF.

* Model Training: Uses Logistic Regression to classify emails.

* Model Evaluation: Outputs the accuracy of the model on both training and test data.

Prediction: Classifies an input email message as either "Spam" or "Ham".

Prerequisites
Before running the code, ensure you have the following Python libraries installed:

numpy

pandas

scikit-learn

You can install them using the following command:
