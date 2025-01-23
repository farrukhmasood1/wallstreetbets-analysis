# wallstreetbets-analysis
Sentiment analysis - impact of retail investors on the subreddit r/wallstreetbets on the financial market performance of GME

### Summary

In this project we evaluate the impact of posts and comments made by individuals on r/wallstreetbets - a subreddit where users discuss stock and options trading. The popularity of r/wallstreetbets intensified during early 2021, and it is said to be pivotal in the GameStop short-squeeze in January. For this paper, we have collected roughly 3 million posts and comments made on the subreddit during January and February 2021. We performed sentiment analysis on the collected data using VADER, a subset of the python library, NLTK. We then mapped the daily quantified aggregated sentiment on the subreddit with the actual stock prices to view any correlation between the both. We also perform the same analysis on certain trending stocks at the time rather than the entire market and analyze if there is any difference in results. Some of our key findings include the discovery that there is some correlation between the sentiment and price movement, however, there is a time series lag between the two due to stock investment being a reactionary phenomenon. It also contradicts the popular notion that large institutions and influential investors are the only ones who move the market. 

Main code is in the .ipynb file.

Link to the full paper: https://docs.google.com/document/d/10CPLfY5Q_HsoepUjo2TtCcpqRQdZkDnQnlQJOvun6-I/edit?usp=sharing

Feel free to share your thoughts on this on my email: fmasood@andrew.cmu.edu
