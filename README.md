# Wrangle-and-Analyze-Data
The goal of this project is to wrangle, analyze and then visualize a dataset. The dataset used is the popular twitter account WeRateDogs. 
This account rates people's dogs with humorous comments about the dog. These ratings always have denominator of 10 & ratings go as 11/10, 
12/10, 15/10. 
The archive contains basic tweet data for all tweets as they stood on August 1, 2017.

For wrangling process, the data is gathered from 3 different sources.
1. A csv file, provided by udacity, twitter archive containing all the information about the tweets.
2. image file, which contains information about dog breed. Each dog image is ran through a neural network that classify dog's breed.
3. Using the tweet ID's from archive in mentioned in 1. querying the Twitter API for each tweet's JSON data using Tweepy library.
   Storing this entire set of JSON data in a file called tweet_json.txt.

Then assessing and cleaning all the data for analysis and creating Visualizations.
