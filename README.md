# Stock Prediction using ElasticSearch on [r/wallstreetbets](https://www.reddit.com/r/wallstreetbets/)
## About the Project
> This project uses Elastisearch on posts from the wallstreetbets. We aim to search text in individual posts, and use a variety of metrics, such as sentiment analysis, to correlate text to desirable or undersirable stocks. This information will be used to guide a user to invest in certain stocks.

![r/wallstreetbets icon](https://a.thumbs.redditmedia.com/w-gbSE-QjkUuNjq2yPpekzEtN4CXRiL4tTO_XfloH80.png)
We'll be collecting text data from r/wallstreetsbets using Elastisearch, and saving the sentiment of the text in conjunction with the stock in question. We will draw inferences in this way as part of a stock investment strategy.

## Reddit API Changes
> [An Update Regarding Reddit's API](https://www.reddit.com/r/reddit/comments/12qwagm/an_update_regarding_reddits_api/): Effective July 1st, 2023, we will not be able to access the Reddit API for free. Spending money to support API access through PRAW is currently not in the scope of this project.

To adapt, we've opted to collect Reddit data running up to June 2023. PRAW will not be an active part of our Stock Investment Bot. The bot will function more like a wayback machine rather than a bot which can make investments for the future.
## Usage
- Originally, this bot would frequently search through r/wallstreetbets, analyzing posts through stock to post and post to stock processing,  and sentiment analuysis, to make investments in real time.
- Instead, investments will be made retroactively on posts before July 2023. The bot will not have a live function.

## Technologies

## Features
### ElasticSearch
- Allows us to rapidly match Reddit posts with their mentioned stocks using key identifiers. This helps us towards minimizing the number of posts that are used during the evaluation phase, and matches posts with the most relevant stocks.
### Stock Investment Strategy
![image](https://github.com/Bear-ish-Bets/.github/assets/72900975/2b1be666-612a-4f35-bcfa-283135c6fe80)

### Automatic Stock Investment
We use the Alpaca API to directly make stock investments from the bot using imaginary money (Alpaca features can be used with real money - not recomended with this project!)

## Organization

### Directories:
Official Bear-ish-Bets-Bot:
> The action happens here.

Demos:
> Testing of individual technologies utilized in the sotck investment bot.
- AlpacaDemo - 
- ElasticDemo - demo for Fuzzy Search
- RedditDemo - demo of PRAW API
- Post2StockProcessing - demo of NLP libraries
- SentimentAnalysisDemo - demo of transformers/pipeline libraries
- Stock Price Demo

## Authors
- Michael Lavelle
- Chang Lu
- Trevor Westin
- Alex Yang
- Alfie Zhang
