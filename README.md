# Spam-Email-Filtering-
Application of naive bayes to filter spam emails, from scratch.

## 🔍 Overview

The classifier works by:

1. Reading a dataset of emails labeled as spam or not spam.  
2. Calculating **word frequencies** and **probabilities** for both spam and non-spam emails.  
3. Applying **Naive Bayes classification** using log probabilities to avoid underflow.  
4. Predicting new emails as **spam (`1`)** or **not spam (`0`)**.  

---

## ⚙️ Features

- Calculates **prior probabilities** for spam and not-spam emails.  
- Uses **Laplace smoothing** for unseen words.  
- Applies **logarithmic probabilities** for numerical stability.  
- Evaluates model performance on a separate test dataset.  


![Model Accuracy](https://img.shields.io/badge/Accuracy-94.57%25-brightgreen)


## 📂 Dataset

| Dataset Name | Description | Source |
|--------------|------------|--------|
| Emails Training Dataset | Labeled email features for training the Naive Bayes model | [Kaggle Link](https://www.kaggle.com/datasets/balaka18/email-spam-classification-dataset-csv) |
| Emails Test Dataset | Raw email text with spam labels for testing | [Kaggle Link](https://www.kaggle.com/datasets/noeyislearning/spam-emails) |
