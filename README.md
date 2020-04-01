# Cryptocurrency Sentiment Analysis: Bitcoin & Ethereum

With all of the hype in the news about cryptocurrency, this project will take stock of the latest news headlines regarding Bitcoin and Ethereum to get a better feel for the current public sentiment around each coin.

This project applied natural language processing to understand the sentiment in the latest news articles featuring Bitcoin and Ethereum. This project also applied fundamental NLP techniques to better understand the other factors involved with the coin prices such as common words and phrases and organizations and entities mentioned in the articles.

The following is a list of the project's undertaking:

1. Sentiment Analysis
2. Natural Language Processing
3. Named Entity Recognition]

- - -

#### Sentiment Analysis

Used the newsapi to pull the latest news articles for Bitcoin and Ethereum and created a DataFrame of sentiment scores for each coin.

Used descriptive statistics to answer the following questions:

> Which coin had the highest mean positive score?
>
> Which coin had the highest negative score?
>
> Which coin had the highest positive score?

#### Natural Language Processing

In this section, this project used NLTK and Python to tokenize the text for each coin. Some extra steps taken are as follows:

1. Lowercase each word
2. Remove punctuation
3. Remove stop words

Next, looked at the ngrams and word frequency for each coin.

1. Used NLTK to produce the ngrams for N = 2.
2. Listed the top 10 words for each coin.

Finally, generated word clouds for each coin to summarize the news for each coin.

#### Named Entity Recognition

In this section, the project built a named entity recognition model for both coins and visualize the tags using SpaCy.

## Built With

* [Python](https://www.python.org/) - Programming language.
* [Pandas](https://pandas.pydata.org/) - Data analysis and manipulation tool.
* [newsapi](https://newsapi.org/) - API used to access news articles.
* [Vader Sentiment Analysis](https://github.com/cjhutto/vaderSentiment) - Rule based sentiment analysis tool

## Authors

* **Roberto Cantu**  - [GitHub](https://github.com/RCantu92)