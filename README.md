# Amazon Product Reviews Sentiment Analysis
## 📌 Overview
### This project builds a sentiment analysis pipeline for product or service reviews.
### It performs:

Data preprocessing (cleaning, tokenization, lemmatization, stopword removal)

Feature extraction with TF-IDF and CountVectorizer

Model training with Logistic Regression and Multinomial Naive Bayes

Evaluation using accuracy, classification report, and confusion matrix

Visualization of the most frequent positive and negative words

## 📂 Dataset
The notebook expects a CSV file named (Reviews.csv) with at least:

Text — review text

Sentiment — target label (positive/negative)

You can replace Reviews.csv with your own dataset.

## Steps performed in the notebook:

1- Load and inspect the dataset

2- Preprocess the text (cleaning, tokenizing, lemmatizing)

3- Vectorize text with TF-IDF and CountVectorizer

4- Train Logistic Regression and Multinomial Naive Bayes

5- Evaluate using accuracy, confusion matrix, and classification report

6- Visualize common words for each sentiment


## 📦 Dependencies
Python 3.8+

pandas, numpy

scikit-learn

nltk

spacy

matplotlib, seaborn

tqdm, joblib


## Clone Repostory

git clone https://github.com/Mohamed-Kenawy/Amazon_Product_Reviews_Sentiment_Analysis.git



