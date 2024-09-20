Sentiment Analysis - US Airline Tweets
This project focuses on performing sentiment analysis on the US Airline Sentiment Dataset, which contains data for over 14,000 tweets. The task is to predict the sentiment of each tweet as positive, negative, or neutral.

Overview
The objective of this project is to build a machine learning model that predicts the sentiment of a tweet. The dataset used consists of airline-related tweets from various users. Sentiments are categorized into three classes: positive, negative, and neutral.

Files Provided
Training Data: CSV file containing X_train (input features) and Y_train (sentiment labels).
Test Data: CSV file containing X_test (input features only). The task is to predict the sentiments for this data and submit the results.
Instructions
Train a machine learning model on the provided training dataset (X_train and Y_train).
Predict sentiments for the test data (X_test).
Submit a CSV file with predictions for X_test, without any headers, and containing only one column with the sentiment predictions.
Submit the Jupyter Notebook (.ipynb file) used to build the model.
Features
Data preprocessing including text cleaning, tokenization, and vectorization.
Sentiment prediction using various machine learning algorithms.
Model evaluation based on prediction accuracy.
Dataset
The dataset consists of over 14,000 tweets, which are classified into one of three sentiment categories:

Positive
Negative
Neutral
Columns in the Dataset:
tweet_id: The unique ID of the tweet.
airline: The airline to which the tweet refers.
airline_sentiment: The sentiment of the tweet (positive, negative, or neutral).
text: The tweet's content.

Model
Multiple machine learning models may be explored in the project, including:

Logistic Regression
Support Vector Machines (SVM)
Random Forest
Naive Bayes
