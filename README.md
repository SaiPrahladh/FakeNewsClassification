# FakeNewsClassification
## The Problem:
The problem we were working on is the classification of an article as fake news or not, which is quite rampant given the reach of various media in today's date. Our project looks at various methods which are common in NLP and our aim is to see which one can perform optimally for a bag of words model.
## Data Collection :
We have considered reputed a sources like the New York Times  and the Guardian as the sources of our real dataset . We have used their API’s to extract data from the 2016 news cycle.
For our fake data set we are using data from Kaggle and included several features. This data was collected using the webhose.io API which collected data from 244 websites.

## Usage:
Run the data scrapper notebook to get the data for the authentic news data and combine it to form the complete dataset for training the Naive Bayes model in the fake_news_classification.ipynb and also the Logistic Regression and Random forest algorithms in the Implemenation_LogisticRegression_RandomForrest.ipynb


## Performance Comparison:
| Model                  | Test Accuracy(%) |
|------------------------|------------------|
| Naive Bayes Classifier | 79.83            |
| Random Forests         | 88.88            |
| Logistic Regression    | 88.68            |
