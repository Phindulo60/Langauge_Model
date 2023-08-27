# Natural Language Processing with Disaster Tweets

**Repository owner**: Phindulo60

## Overview

This repository contains a Jupyter notebook that demonstrates the process of Natural Language Processing (NLP) on a dataset of tweets to determine whether a given tweet is about a real disaster or not. The dataset contains various tweets, some of which are about real disasters, while others are not.

## Dataset Description

The dataset consists of the following columns:

- **id**: An identifier for the tweet.
- **keyword**: A keyword from the tweet.
- **location**: The location from where the tweet was sent.
- **text**: The text of the tweet.
- **target**: A binary target, where `1` indicates the tweet is about a real disaster and `0` indicates it's not.

## Steps Covered in the Notebook

1. **Data Loading**: The dataset is loaded into pandas dataframes.
2. **Data Preprocessing**: 
   - Handling missing values.
   - Text cleaning which includes:
     - Removal of URLs, HTML tags, and diacritics.
     - Tokenization, removal of stop words, digits, and punctuation.
     - Lemmatization and stemming.
3. **Feature Extraction**:
   - Bag of Words.
   - Term Frequency-Inverse Document Frequency (TF-IDF).
   - Word Embeddings.
   - N-grams.
4. **Modeling**: Several machine learning models are trained and evaluated, including:
   - Multinomial Naive Bayes.
   - Logistic Regression.
   - Linear Support Vector Classifier.
   - Random Forest Classifier.

## Results

The models were evaluated based on accuracy, precision, recall, and F1 score. The best-performing model and its metrics are highlighted in the notebook.

## How to Use

1. Clone the repository.
2. Ensure you have the required libraries installed (pandas, numpy, scikit-learn, gensim, etc.).
3. Open the Jupyter notebook and run the cells sequentially.

## Contributions

Contributions are welcome! Please read the contribution guidelines before making any changes.
