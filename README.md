# Naive Bayes Text Classifier — Spam Detection
A simple but effective project using Naive Bayes Classification to detect whether a message is spam or ham (not spam). Built using Python and Scikit-learn, this project demonstrates how machine learning can be applied to real-world text classification problems.

# Project Overview
This project applies a Multinomial Naive Bayes classifier to detect spam messages in SMS text data. It includes:

Preprocessing of real-world labeled SMS data

Feature extraction using CountVectorizer

Model training with MultinomialNB (Naive Bayes)

Classification of custom messages

Evaluation using accuracy and classification report

# Dataset
We use the SMS Spam Collection Dataset (from UCI ML Repository), which contains 5,000+ labeled SMS messages marked as spam or ham.

# How It Works
Load Dataset
Reads a CSV file with two columns: label (spam/ham) and message.

Preprocess & Vectorize
Converts text messages into numerical feature vectors using CountVectorizer.

Train Model
Trains a MultinomialNB classifier on the training data.

Test Model
Predicts on unseen messages and evaluates performance.

Classify Custom Input
Allows you to input any number of text messages and predict whether each one is spam or not.

# Model Performance
Accuracy: ~98%

Classification Report: Includes precision, recall, and F1-score

# Technologies Used
Python 3

Scikit-learn

Pandas

NumPy
