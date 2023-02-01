# Subreddit_Sentimental_Analysis

Project done in notebook form to experiment with NLP techniques

## Method of gathering data and processing:

Pulls the top 100 hot posts from a specified subreddit

Analyzes the comments of those max. 100 posts up to depth of 5 in a single comment thread

Cleaning the contents of the comments is done through reg library and stopwords from NLTK

At first comments are Tokenized, Lemmatized and then we take a Frequency distribution of them in order to visualize the most used words.

N-grams are looked at for more information how these words are used (take 3-gram)

Sentiment Analysis is lastly done using NLTK's SentimentIntensityAnalyzer

Results are considered positive if the compound value is > 0.2 and negative if compound value < -0.2, otherwise neutral.

These positive, negative and netural values are then visualized using seaborn.
