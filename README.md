# Cryptocurrency Sentiment Analysis: Bitcoin & Ethereum

This project aims to produce a sentiment analysis of crypto, specifically with Bitcoin and Ethereum. The reason this is valuable is that it provides a quick snapshot of the overall sentiment of both blockchains. This information could then be used to inform certain decisions regarding the respective blockchains.

## Getting Started

### Prerequisites

For this project, you will need a newsapi key. You can get the key here by clicking "Get API Key" on [this](https://newsapi.org/) page.

### Installing

Installation of the necessary tools is as follows:

JupyterLab

```
pip install jupyterlab
```

Vader Sentiment Analysis
```
pip install vaderSentiment
```

Natural Language Toolkit (NLTK

```
pip install --user -U nltk
```
WordCloud

```
pip install wordcloud
```
Matplotlib

```
pip install -U matplotlib
```
spaCy

```
pip install spacy
```
---

# Project Findings:

## Sentiment Analysis Report:

>	Which coin had the highest mean positive score?

Bitcoin  had the highest mean possible score with 0.0652 over Ethereum's 0.059.

>	Which coin had the highest negative score?

Bitcoin had the highest max compound score with 0.688 over Ethereum's 0.625.

>	Which coin had the highest positive score?

Ehtereum had the highest max positive score with 0.139 over Bitcoin's 0.117.

## Natural Language Processing Report:

The Bitcoin word cloud, after tokenizing all of the text, was very unexpected, especially due to the fact that it seemed to have repeating articles after being pulled from the News API. Perhaps, a specific source or approach could have been suggested to be used to pull the data.

On the other hand, Ethereum did not yield a surprising word cloud, but did provide interesting results.


## Named Entity Recognition Report:

The Named Entity Recognition yielded similar results to the NLP report, but it WAS helpful to see a list of the named entities for both Bitcoin and Ethereum.

A PDF of the findings can be found in:

```
./Code/crypto_sentiment.pdf
```

---

## Built With

* [Python](https://www.python.org/) - Programming language.
* [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/index.html) - Next-generation web-based user interface for Project Jupyter.
* [Pandas](https://pandas.pydata.org/) - Data analysis and manipulation tool.
* [pprint](https://docs.python.org/3/library/pprint.html) - Module providing a capability to “pretty-print” arbitrary Python data structures in a form which can be used as input to the interpreter.
* [newsapi](https://newsapi.org/docs) - API used to access news articles.
* [Vader Sentiment Analysis](https://github.com/cjhutto/vaderSentiment) - Rule based sentiment analysis tool.
* [Natural Language Toolkit (NLTK)](https://www.nltk.org/) - Leading platform for building Python programs to work with human language data.
* [Regular Expression Operation (Re)](https://docs.python.org/3/library/re.html) - Module providing regular expression matching operations.
* [Collections](https://docs.python.org/3/library/collections.html) - Module providing specialized container datatypes alternatives to Python.
* [WordCloud](http://amueller.github.io/word_cloud/index.html) - Word cloud generator in Python.
* [Matplotlib](https://matplotlib.org/index.html) - Comprehensive library for creating static, animated, and interactive visualizations in Python.
* [spaCy](https://github.com/explosion/spaCy) - Library for advanced Natural Language Processing in Python and Cython.

## Authors

* **Roberto Cantu**  - [GitHub](https://github.com/RCantu92)