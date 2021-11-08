# NLP (Natural Language Processing)

## Background

This project will explore and  apply natural language processing to understand the sentiment in the latest news articles featuring Bitcoin and Ethereum. 

We will demonstrate and apply fundamental NLP techniques to better understand the other factors involved with the coin prices such as common words and phrases and organizations and entities mentioned in news articles.

The following topics will be uncovered in this project:

1. [Sentiment Analysis](#1---Sentiment-Analysis)
2. [Natural Language Processing](#2---Natural-Language-Processing)
3. [Named Entity Recognition](#3---Named-Entity-Recognition)

---


## Installations

To run the .ipynb file please run the following commands in terminal to have the necessary libraries installed:

- python -m pip install newsapi-python
- conda install -c conda-forge wordcloud 
- python -m spacy download en_core_web_sm


An API key will also be required, please obtain keys from here:
https://newsapi.org/docs/


- in the main directory create a file called .env and have the following content in it:
<br>news_api = "API KEY"