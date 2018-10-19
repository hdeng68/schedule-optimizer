# Tweets and Emojis
Scraping tweets from the Twitter API. Analyzing emotion distribution around the world based on user location and emoji use from the tweets. A project conducted under the Berkeley Affective Cognitive Neuroscience Lab.

## Part 1: Scraping Old Tweets
Code written in Python to get old tweets. It bypasses the time constraint limitations of Twitter Official API. Code adapted from Jefferson Henrique's GetOldTweets to include geolocation and scrape emojis instead of text.

### Components
- **Tweet:** Model class describing the scraped tweet format.
- **TweetManager:** A manager class to help get tweets in **Tweet**'s model.
- **TwitterCriteria:** A collection of search parameters to be used together with **TweetManager**.
- **Main:** Examples of how to use.
- **Exporter:** Exports tweets to a .csv file named "output_got.csv".