# Fake-News-Detection

## Overview

The Fake News Detection project aims to build a machine learning model that can identify whether a given news article is real or fake. The solution is designed to help mitigate the spread of misinformation by analyzing the content of news articles and predicting their authenticity based on linguistic patterns and other features.

## Features

1) Data Preprocessing: Tokenization, stop word removal, lemmatization, and vectorization of news articles.
2) Model Training: Trains various machine learning models (e.g., Logistic Regression, Naive Bayes, Random Forest) for binary classification.
3) Prediction: Predicts whether a news article is real or fake based on text input.
4) Evaluation: Provides performance metrics like accuracy, precision, recall, and F1-score for model evaluation.
5) User Interface (Optional): A simple web app interface for users to input news articles and get instant predictions.

## Dataset

The dataset typically contains two columns:

1) Text: The text content of the news article.
2) Label: The binary label indicating whether the article is real (1) or fake (0).
3) You can either use publicly available datasets like the Kaggle "Fake News" dataset or any other dataset that fits the project scope.

## Models Used

The project explores several machine learning models to detect fake news:

1) Logistic Regression
2) Naive Bayes
3) Random Forest
4) Support Vector Machine (SVM)
The final model is selected based on its performance on validation data, and it can be further fine-tuned for better results.
