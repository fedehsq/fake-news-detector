# Fake news detector

A Machine Learning model that detects fake news.

## Dataset ([ISOT Fake News Dataset](https://drive.google.com/open?id=1IoTRrJNDJqvaG3hnUpnHQyGvPAJbO8y3))

The dataset contains two types of articles: fake and real news. \
Articles were collected from real sources:

1. Truthful articles were obtained by crawling articles from Reuters.com (News website).
2. Fake articles were collected from unreliable websites that were flagged by Politifact and Wikipedia.\
The dataset contains different types of articles on different topics; however, the majority of articles focus on political and World news topics.

## Workflow

The classification has been made with four different classifier:

1. Multinomial NB
2. Linear SVC
3. Logistic Regression
4. Decision Tree

With and without stemming and stopwords removal,
with CountVectorizer and TfidfVectorizer
and with k-cross validation for the best trials to verify the obtained results.

For more details and to see the results, read the [FAKE NEWS DETECTOR](./FAKE%20NEWS%20DETECTOR.pptx) presentation.

##  Instructions

1. ``` virtualenv venv ```
2. ``` source venv/bin/activate ```
3. ``` pip install -r requirements.txt ```
4. run the notebook

## Authors

* [Federico Bernacca](https://github.com/fedehsq)

* [Paola Petri](https://github.com/paolapetri)