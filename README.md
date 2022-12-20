# Sentiment analysis of video game tweets
 Video game sentiment analysis is the process of analyzing public sentiment towards video games. It involves collecting tweets about video games and using natural language processing (NLP) techniques to analyze the sentiment of the tweets. This analysis can help video game companies better understand their audience and make decisions about marketing and product development.

In this project we will use the Python textblob library to perform sentiment analysis on video game related tweets. Textblob is a library for processing textual data and is built on top of the popular NLTK library. It provides simple API for diving into common natural language processing (NLP) tasks such as part-of-speech tagging, noun phrase extraction, sentiment analysis, classification, translation, and more. 

The first step is to collect the tweets. We can do this using the Twitter API and the Tweepy library. We will collect the tweets about video games using a specific hashtag or keyword. 

Once we have the tweets, we can use textblob to analyze the sentiment of each tweet. Textblob provides two sentiment analysis methods: sentiment and subjectivity. The sentiment method returns a tuple of the form (polarity, subjectivity) where polarity is a float within the range [-1.0, 1.0] and subjectivity is a float within the range [0.0, 1.0] where 0.0 is very objective and 1.0 is very subjective.

Once we have the sentiment scores for each tweet, we can visualize the results. We can use matplotlib or seaborn to create a bar chart showing the distribution of sentiment scores. This will give us an idea of how the public feels about the video game.

By performing sentiment analysis on video game related tweets, game companies can get a better understanding of how their audience feels about their games. This can help them make better decisions about marketing and product development.
