WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. The account was started in 2015 by college student Matt Nelson, and has received international media attention both for its popularity and for the attention drawn to social media copyright law when it was suspended by Twitter for breaking these aforementioned laws. 
In this project we are going to wrangle and analyze the tweet archive of Twitter user @dog_rates.
This archive contains basic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of their tweets as they stood on August 1, 2017, to make this Twitter archive "enhanced." Of the 5000+ tweets, it has been filtered for tweets with ratings only (there are 2356).
In this notebook, We are going to read the archive and download the missing data (retweet count and favorite count) via twitter API, w'll download also the tweet image predictions data using python requests, w'll assess and clean our datasets next, finally we analyze the cleaned versions where w'll try to see the relationship between dog category and/or ratings and twitter metrics (favorite, retweet), our analysis will answer the following questions:
Do the rating affect the popularity of the tweet ?
Do the dog stage or breed affect the rating ?
Is there any dog stage or breed more popular than the others ?
