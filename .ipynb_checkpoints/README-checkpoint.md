# NLP Homework

## Background

This project aims apply natural language processing to understand the sentiment in the latest news articles featuring Bitcoin and Ethereum. It will also apply fundamental NLP techniques to better understand the other factors involved with the coin prices such as common words and phrases and organizations and entities mentioned in the articles. The latest articles were pulled using the [newsapi](https://newsapi.org/). The file include:

[Crypto Sentiment](crypto_sentiment.ipynb)

- - -

## Summary of Analysis

#### Sentiment Analysis

A dataframe of sentiment scores was created for each coin.

1. BTC Sentiment

![BTC](images/BTC.PNG)

2. ETH Sentiment

![ETH](images/ETH.PNG)

In summary, ETH had the highest mean positive score, the higest compound score. and the highest positive score.

#### Natural Language Processing

1. NTLK was used to tokenize the text for each coin
2. NTLK was used to produce bygrams for each coin
3. NTLK was used to produce top 10 words for each coin
4. Words clouds were produced for each coin

![BTC WC](images/BTCWC.PNG)

2. Easy Ensemble Classifier

![ETH WC](images/ETHWC.PNG)

#### Named Entity Recognition

A named entity recognition model was built for each coin using SpaCy

![BTC NER](images/BTCNER.PNG)

![ETH NER](images/ETHNER.PNG)