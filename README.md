# Kaggle--Email-Classification-NLP
Build a Multinomial Naive Bayes model to detect spam emails and compare CountVectorizer and TfidfVectorizer in the model

## Introduction
Use CountVectorizer and TfidfVectorizer to build two pipelines with MultinomialNB. By tuning hyperparameters, I will compare the two results from the pipelines and decide which text transformer is better in this case. In this capacity, we want a model that can predict well for both classes, spam and non-spam, since we don't have a model that can find out all the spam emails, but in the meanwhile, many non-spam emails go to the spam folder. Therefore, the results will be based on the accuracy and f1 scores.

## Results
In this case, CountVectorizer is slightly better than TfidfVectorizer, with a higher spam f1 score. The final model has a 0.91 accuracy score, a 0.90 f1 score on the non-spam class, and a 0.92 f1 score on the spam class.

## Data
The data is from https://www.kaggle.com/datatattle/email-classification-nlp
