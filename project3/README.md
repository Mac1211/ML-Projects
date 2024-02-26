# Overview:

This repository contains Python code for sentiment analysis on restaurant reviews using Natural Language Processing (NLP) techniques. The goal is to classify reviews as positive or negative based on their content.The dataset used in this project is Restaurant_Reviews.tsv. It consists of restaurant reviews along with their labels (positive or negative). The data is tab-separated. The dependencies are numpy, Matplolib, pandas, scikit-learn and NLTK. Additionally, you need to download NLTK's stopwords data. You can do this by running the following command: python -m nltk.downloader stopwords
# Contents:

1. nlp_restaurant_reviews.py: Python script for sentiment analysis on restaurant reviews using NLP techniques.
2. Restaurant_Reviews.tsv: Dataset containing restaurant reviews and their labels.
3. README.md: This file providing an overview of the project.

# Result:

The script outputs the predictions for test set reviews along with their actual labels. 
It also calculates the confusion matrix and accuracy score to evaluate the performance of the sentiment classifier.