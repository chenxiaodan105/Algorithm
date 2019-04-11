# Xiaodan's Directory

## Contents
[1. Text Preprocessing](#text-preprocessing)

[2. Imbalance Data Handling](#imbalance-data-handling)

[3. Negation Handling](#3.-Negation-Handling)

[4. Methods](#methods)

[5. Grid Search](#Grid-Search)


## 1. Text Preprocessing
* tokenization
* remove stopwords
* remove special characters
* stemming and lemmatization

## 2. Imbalance Data Handling
* smote 
* balanced ensemble method using SVM or decision tree as base model
* [reference](https://imbalanced-learn.org/en/stable/ensemble.html)

## 3. Negation Handling
* for a specific speech, parse the key sentence using spacy
* find both the scope and the key word in the sentence
* within the scope, count the number of the negation words, if it's even, it's not a negation, if it's odd, it's a negation

## 4. Methods
* 4.1 stance detection

| method |  F1 score(majority) | F1 score(minority) |
| ----------- | ----------- | ----------- | 
| bow + svm |  |
| tfidf + svm | |
| bow + random forest | |
| tfidf + random forest | |
| bow + BalancedBaggingClassifier | |
| tfidf + BalancedBaggingClassifier | |
| word2vec + lstm | |
| word2vec + BiLSTM + encoding | |


* 4.2 stance classification

| method |  F1 score(majority) | F1 score(minority) |
| ----------- | ----------- | ----------- | 
| bow + svm |  |
| tfidf + svm | |
| bow + random forest | |
| tfidf + random forest | |
| bow + BalancedBaggingClassifier | |
| tfidf + BalancedBaggingClassifier | |
| word2vec + lstm | |
| word2vec + BiLSTM + encoding | |


## 5. Grid Search
* grid search for tfidf and bow, including ngram, max_df, min_df, stop_words, max_features, etc.
* grid search for machine learning models(LR, SVM, random forest, naive bayes)






