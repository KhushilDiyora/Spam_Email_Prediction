# Spam Email Classification using Logistic Regression

This repository contains a spam email classifier built using Logistic Regression and TF-IDF for feature extraction. The model classifies emails into two categories: spam or ham (non-spam).

# 🗺️ Overview

The project uses a dataset of email messages, which are classified as either spam or ham. The model uses Logistic Regression for classification after transforming the email messages into numerical feature vectors using TF-IDF (Term Frequency-Inverse Document Frequency). The classifier is then evaluated based on its accuracy on both training and test datasets.

# ⭐ Features

* Data Preprocessing: Handles missing data and encodes labels ('spam' as 0 and 'ham' as 1).

* Text Feature Extraction: Converts text data into numerical vectors using TF-IDF.

* Model Training: Uses Logistic Regression to classify emails.

* Model Evaluation: Outputs the accuracy of the model on both training and test data.

* Prediction: Classifies an input email message as either "Spam" or "Ham".

# ✅ Prerequisites

Before running the code, ensure you have the following Python libraries installed:

* `numpy`

* `pandas`

* `scikit-learn`

You can install them using the following command:
    
    pip install numpy pandas scikit-learn

# 📊 Dataset

The dataset mail_data.csv should contain the following columns:

* Category: Target variable (either "spam" or "ham").

* Message: The email content that needs to be classified.

# 🏷️ Categories

* Spam: Unsolicited or unwanted email.

* Ham: Legitimate, non-spam email.

# 📂 Files

* spam_classifier.py: Python script for building and evaluating the spam classifier.

* mail_data.csv: Sample email dataset (with "Category" and "Message" columns).


# 💡 Example

The script will output something like this:
            
    Accuracy on training data: 0.978
    Accuracy on test data: 0.973
    [1]
    Ham mail

# ⚙️ Custom Prediction

You can change the input_mail variable in the script to classify any custom email message. For example:

    input_mail = ["I've been searching for the right words to thank you for this breather..."]

The model will predict if the message is spam or ham.

# 📌 Notes

* TF-IDF is used for feature extraction, which helps in handling large datasets by converting text data into useful features.

* Logistic Regression is used for classification, but you can experiment with other algorithms for improved accuracy.

* This project is intended to be a basic demonstration and can be extended with more advanced techniques like Naive Bayes, Support Vector Machines, or deep learning approaches.

