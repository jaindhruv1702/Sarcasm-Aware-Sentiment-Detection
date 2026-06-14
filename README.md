# Sarcasm-Aware-Sentiment-Detection
# Sarcasm-Aware Sentiment Detection for Ethical Social Media Analysis

## Overview

This project implements a hybrid Natural Language Processing (NLP) pipeline for sarcasm-aware sentiment analysis. Traditional sentiment analysis systems often misclassify sarcastic content because literal sentiment differs from intended meaning. This system combines machine learning, transformer-based sentiment analysis, and rule-based linguistic reasoning to improve sentiment interpretation.

## Problem Statement

Social media content frequently contains sarcasm, irony, and rhetorical statements that can mislead standard sentiment analysis models. The objective of this project is to identify sarcastic expressions and improve sentiment classification reliability.

## Dataset

Dataset Source: Kaggle

The dataset contains social media headlines and text samples labeled for sarcasm detection.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* NLTK
* DistilBERT
* Matplotlib
* Seaborn

## Methodology

### Data Preprocessing

* Text cleaning
* Tokenization
* Stopword removal
* Feature extraction

### Machine Learning

* TF-IDF Vectorization
* Logistic Regression

### Sentiment Analysis

* DistilBERT Transformer Model

### Sarcasm Detection

Custom linguistic rules were implemented to identify:

* Irony
* Mock praise
* Contradictory sentiment
* Rhetorical sarcasm

## Features

* Sarcasm Detection
* Sentiment Classification
* NLP Pipeline
* Transformer-Based Analysis

## Future Improvements

* Fine-tuned transformer models
* Real-time web application
* Explainable AI dashboard
* Multi-language support

## Author

Dhruv Jain
