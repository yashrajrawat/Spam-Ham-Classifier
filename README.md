# Email Spam Classifier (Kaggle Challenge)
A Machine Learning classic starter project using Python libraries to cluster a data set of 'sms' messages into 'spam' and 'ham' using Naive Bayes. The dataset is a collection of 5,574 SMS messages taken from the UCI Machine Learning repository, which need to be tagged as "spam" and "ham".
## The whole pipeline consists of the following steps:
#### Loading data
#### Data wrangling and pre-processing
#### Feature Selection 
#### Feature Vector 
#### Modelling Evaluation 
#### Writing results

## Following techniques, packages and functions have been used:
#### (Natural Language Toolkit) NLTK
#### Tokenization
#### Removal of Stopwords
#### Stemming
#### Lemmatizing
#### Bag of Words (BoW) or CountVectorizer
#### TF-IDF Vectorizer
#### Feature Engineering
#### Random Forest Classifier
#### GridSearchCV
#### Cross-Validation
#### Model Evaluation metrics (precision, recall, fscore, accuracy, confusion matrix)

I have achieved an overall accuracy of 98% by implementing the Naive Bayes on datasets modeled with both TF-IDF algorithm and Count Vectorizer method (Bag of Words) and compared their model evaluation metrics. Using Naive Bayes algorithm for both TF-IDF Vectorizer model and Count Vectorizer model gave us the same values for all metrics:

## TF-IDFVectorizer model:

Precision: 1.0 / Recall: 0.846 / F1-Score: 0.916 / Accuracy: 0.979
Confusion Matrix for TF-IDFVectorizer model tells us that we correctly predicted 966 hams and 126 spams.0 hams were incorrectly identified as spams and 23 spams were incorrectly predicted as hams.

## Count Vectorizer Model:
Precision: 1.0 / Recall: 0.852 / F1-Score: 0.92 / Accuracy: 0.98
Confusion Matrix for Count Vectorizer Model tells us that we correctly predicted 966 hams and 127 spams.0 hams were incorrectly identified as spams and 22 spams were incorrectly predicted as hams.

## Check out the live demo: https://esc-yshrwt.herokuapp.com/
