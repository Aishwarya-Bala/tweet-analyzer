# Tweet Analyzer
Web based application to analyze the tweets using sentimental analysis.

Major steps in this program are:

1. Authorize twitter API client.
2. Make a GET request to Twitter API to fetch tweets for a particular query.
3. Parse the tweets. Classify each tweet as positive, negative or neutral.

The Sentiment classifier is created using the following steps.

1. TextBlob uses Movie Reviews Dataset in which the reviews are already labelled as positive or negative.
2. Positive and Negative features are extracted from each positive and negative review respectively.
3. Training data now consists of labelled positive and negative features. The data is trained on Naive Bayes Classifier.

Then sentiment polarity method of TextBlob class is used to get the polarity of tweet betweet -1 and 1.

Finally the parsed tweets are returned. In this program I have tried to find the percentage of positive, negative and neutral tweets about a query.
