# Article Classification

This project is about classifying articles into different categories. The categories include 'art', 'economy', and 'sport'. The project uses Natural Language Processing (NLP) techniques to preprocess the text data and convert it into numerical features that can be used for machine learning.

## Preprocessing

The text data is preprocessed by tokenizing the text, converting to lowercase, removing stopwords, and applying stemming.

## Feature Extraction

The TF-IDF (Term Frequency-Inverse Document Frequency) vectorizer is used to convert the preprocessed text data into numerical features.

## Models

Two models are used for the classification task: Naive Bayes and Support Vector Machine (SVM). The performance of the models is evaluated using accuracy, confusion matrix, and classification report.

## Usage

To classify a new article, simply input the text of the article into the `predict` function of the trained model. The function will output the predicted category of the article.
