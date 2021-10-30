# Tales-from-the-Crypto

Before use, make sure to replace the <INSERT_API_KEY> in .env file with your API key, which can be obtained from this link
(https://newsapi.org/)

## 1. Sentiment Analysis

Used the newsapi to pull the news articles for Bitcoin and Ethereum and created a DataFrame of sentiment scores for each coin. Also, calculated descriptive statistic as well for both coins. Below are the answers to questions based on those statistics.

> Which coin had the highest mean positive score?

- Bitcoin

> Which coin had the highest compound score?

- Ethereum

> Which coin had the highest positive score?

- Bitcoin

> Which coin had the highest negative score?

- Ethereum

## 2. Natural Language Processing

Used NLTK and python to tokenize the text for each coin. Following techniques used.

- Lowercase each word
- Remove Punctuation
- Remove Stopwords

Then NGrams and Frequency Analysis performed

- Used NLTK to produce the n-grams for each coin
- Listed Top 10 words for each coin

Then produced the Word Clouds for each coin

> Bitcoin Word Cloud

![Bitcoin Word Cloud](https://github.com/chirathlv/Tales-from-the-Crypto/blob/main/Images/btc_word_cloud.PNG)

> Ethereum Word Cloud

![Ethereum Word Cloud](https://github.com/chirathlv/Tales-from-the-Crypto/blob/main/Images/eth_word_cloud.PNG)
