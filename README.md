# Stock Prediction using Elastisearch on r/wallstreetbets
## About the Project
> This project uses Elastisearch on posts from the wallstreetbets. We aim to search text in individual posts, and use a variety of metrics, such as sentiment analysis, to correlate text to desirable or undersirable stocks. This information will be used to guide a user to invest in certain stocks.
> ![r/wallstreetbets icon](https://a.thumbs.redditmedia.com/w-gbSE-QjkUuNjq2yPpekzEtN4CXRiL4tTO_XfloH80.png)
> We'll be collecting text data from r/wallstreetsbets using Elastisearch, and saving the sentiment of the text in conjunction with the stock in question. We will draw inferences in this way as part of a stock investment strategy.

## Reddit API Changes
> [An Update Regarding Reddit's API](https://www.reddit.com/r/reddit/comments/12qwagm/an_update_regarding_reddits_api/). This policy will be in effect on July 1st, 2023, and will limit free access to the Reddit API.

To adapt, we've opted to collect Reddit data running up to June 2023. PRAW will not be an active part of our Stock Investment Bot. 
## Usage

## Technologies

## Features
### ElasticSearch
- Allows us to rapidly match Reddit posts with their mentioned stocks using key identifiers. This helps us towards minimizing the number of posts that are used during the evaluation phase, and matches posts with the most relevant stocks.
### Stock Investment Strategy
![image](https://github.com/Bear-ish-Bets/.github/assets/72900975/2b1be666-612a-4f35-bcfa-283135c6fe80)
### Automatic Stock Investment
todo

## Organization

### Repoes:

Demos:
- AlpacaDemo
- ElasticDemo
  Demo for functionality of Fuzzy Search using Elastisearch
- RedditDemo
  Demo for functionality of PRAW API
- Post2StockProcessing
- Stock Price Demo

## Authors
- Michael Lavelle
- Chang Lu
- Trevor Westin
- Alex Yang
- Alfie Zhang
