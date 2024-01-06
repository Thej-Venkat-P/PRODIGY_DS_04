# Twitter Sentiment Analysis

This project involves performing sentiment analysis on a dataset of tweets. The goal is to train a model that can accurately predict the sentiment of a tweet based on its content.

## Overview

The project follows a comprehensive workflow:

1. **Data Import and Exploration:** We start by importing the necessary modules and loading the dataset. The data is then explored, checked for missing values, and the distribution of sentiments in the training data is visualized.

2. **Data Preprocessing:** The data is preprocessed by converting the categorical columns to numerical values and cleaning the tweet text. This involves removing punctuations, special characters, and numbers. The TfidfVectorizer is used to convert the text into numerical features.

3. **Model Training and Evaluation:** A RandomForestClassifier model is trained on the preprocessed data. The performance of the model is evaluated on a separate testing dataset. The model achieved a training accuracy of 0.708 and a testing accuracy of 0.72.

4. **Model Deployment:** The trained model is saved and a function is created to predict the sentiment of new tweets. This function can be used to analyze the sentiment of new tweets and gain insights from social media data.

## Usage

The project is contained in a Jupyter notebook, `SentimentAnalysis.ipynb`. To use the project, run the notebook cells in order. The final cell contains the function for predicting the sentiment of new tweets.

## Conclusion

This project provides a comprehensive workflow for performing Twitter sentiment analysis. The trained model can be used to analyze the sentiment of new tweets and gain insights from social media data.
