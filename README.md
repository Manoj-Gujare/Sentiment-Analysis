# Sentiment Analysis Project

## Description
This project involves performing sentiment analysis on text data using machine learning techniques. The sentiment analysis is performed on a dataset obtained from Twitter, containing tweets labeled with four types of sentiment: positive, negative, neutral, and irrelevant. The project includes preprocessing the data using the `preprocess_kgptalkie` library, building a machine learning model using a pipeline with `TfidfVectorizer` followed by `RandomForestClassifier`, achieving an accuracy of 91.0%. Additionally, the trained model is saved using `pickle` for future use.

## Dataset
The dataset used for sentiment analysis is stored in the file `twitter_sentiment.csv`. It contains tweets labeled with four types of sentiment: positive, negative, neutral, and irrelevant.

## Preprocessing
The `preprocess_kgptalkie` library is utilized for preprocessing the text data before feeding it into the machine learning model. This library helps in cleaning and preparing the text data for analysis.

## Model Building
The machine learning model is built using a pipeline. The pipeline includes `TfidfVectorizer` for converting text data into numerical features and `RandomForestClassifier` for classification. The model achieves an accuracy of 91.0% on the sentiment analysis task.

## Model Persistence
The trained model is saved using the `pickle` library and stored in the file `twitter_sentiment.pkl`. This allows for easy loading of the model for future use without needing to retrain it.

## Web Application
A web-based application is created using Streamlit, where users can input sentences, and the application predicts the sentiment for each input sentence using the saved machine learning model. The application provides an interactive interface for users to perform sentiment analysis on their text data.

## Usage
1. After installing the dependencies and running the Streamlit application, a web page will open in your default browser.
2. Enter sentences or text inputs into the provided text box.
3. Click on the "Predict" button to see the predicted sentiment for each input sentence.
