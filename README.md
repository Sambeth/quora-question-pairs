# Capstone proposal for Machine learning Nanodegree at Udacity

## Introduction

Over 100 million people visit Quora every month, so it's no surprise that many people ask similarly worded questions. Multiple questions with the same intent can cause seekers to spend more time finding the best answer to their question, and make writers feel they need to answer multiple versions of the same question. Quora values canonical questions because they provide a better experience to active seekers and writers, and offer more value to both of these groups in the long term.

Currently, Quora uses a Random Forest model to identify duplicate questions. In this competition, Kagglers are challenged to tackle this natural language processing problem by applying advanced techniques to classify whether question pairs are duplicates or not. Doing so will make it easier to find high quality answers to questions resulting in an improved experience for Quora writers, seekers, and readers.

## Requirements

* [Python 3.6.x](https://www.python.org/downloads/)
* [Anaconda 5.2](https://www.anaconda.com/download/)

## Required Libraries

pip install nltk tqdm contractions inflect fuzzywuzzy gensim xgboost python-levenstein pymed

## Data

 Train data and test data are available on [Kaggle](https://www.kaggle.com/c/quora-question-pairs/data).

## GloVe file for word2vec

[Glove 6B 300d] (http://nlp.stanford.edu/data/glove.6B.zip)

## Jupyter Notebooks

Quora_Duplicate_Questions.ipynb
Recurrent Neural Network (LSTM).ipynb

### As Jupyter notebooks

Simply run the notebook server using the standard Jupyter command:

    $ jupyter notebook

## Neural Network Architecture

![[Keras model architecture for Quora Duplicate Questions ]](LSTM diagram.png)