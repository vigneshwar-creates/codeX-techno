# Spam Detection Analysis

This project builds a machine learning model to classify SMS messages as either "Spam" or "Ham" (not spam).

## Overview

The model uses a Multinomial Naive Bayes algorithm, a probabilistic classifier well-suited for text classification. The goal is to achieve high accuracy in filtering unwanted messages.

## Dataset

The dataset used is the **SMS Spam Collection Dataset**, which is included in `archive.zip`. It contains over 5,500 labeled messages.

* **Features**: `message` (the text content of the SMS)
* **Target**: `label` (spam or ham)

## How to Run

1.  Unzip `archive.zip` to get the `spam.csv` file.
2.  Make sure you have the required libraries installed (pandas, scikit-learn).
3.  Open `spam_detection.ipynb` in a Jupyter environment (like Jupyter Notebook or Google Colab).
4.  Run the cells sequentially to train the model, see the evaluation, and test a custom message.
