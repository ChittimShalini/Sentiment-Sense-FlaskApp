# Sentiment-Sense-FlaskApp
Sentiment Analysis with Flask and TextBlob

## Overview
Sentiment Sense is a web application designed to analyze the sentiment of movie reviews. Using the TextBlob library, it provides an easy-to-use interface where users can input text and receive an analysis indicating whether the sentiment is positive, negative, or neutral. The app integrates a Flask backend with an HTML/CSS frontend to deliver a seamless user experience.

## Dataset
The dataset used for this project is the "Sentiment Analysis on Movie Reviews" dataset from Kaggle. This dataset includes labeled movie reviews that are used to train and validate the sentiment analysis model. The dataset was downloaded using the Kaggle API command.

## Steps Involved
Data Preparation:

Download the dataset from Kaggle.
Preprocess the data to clean and format it appropriately for analysis.
Split the data into training and testing sets.
Model Training:

Train the TextBlob model (or another chosen sentiment analysis model) on the labeled movie reviews.
Validate the model to ensure accuracy in predicting sentiment.
Text Input:

Users enter the text they want to analyze in the provided textarea on the web page.
Form Submission:

The input text is sent to the Flask backend using an HTML form when the user submits it.
Sentiment Analysis:

The Flask backend processes the text using the trained TextBlob model to calculate the polarity and subjectivity.
Result Display:

The analysis results, including the text, polarity, subjectivity, and sentiment category (positive, negative, or neutral), are displayed on the webpage.

## Usage
To use the Sentiment Sense Flask App, follow these steps:
1)Clone the repository
2)Set up a virtual environment
3)Install the dependencies
4)Run the Flask app
5)Access the Application

## Dependencies
The following dependencies are required to run the Sentiment Sense Flask App:

Flask: A micro web framework for Python.
TextBlob: A Python library for processing textual data.
Pandas: A data manipulation and analysis library for Python.
Kaggle: For downloading datasets from Kaggle.

## Conclusion
The Sentiment Sense Flask App provides a straightforward way to analyze the sentiment of movie reviews or any other text input. By leveraging the TextBlob library and a trained sentiment analysis model, it offers quick and accurate sentiment classification. This application can be useful for various purposes, including monitoring social media, analyzing customer feedback, and more.
