# Twitter-Sentiment-Analysis

The data was fetched from Twitter by using tweepy wrapper around the twitter API. VaderSentiment library was applied to conduct the sentiment analysis. Flask and jinjia2 was selected to write the application. A webserver running at AWS EC2 was deployed.

Since there is a limitation of data fetching for individual Twitter API, currently the results desplay the most 100 tweets from Donald Trump and 100 users who were followed by Donald Trump. The green scale represents positive sentiment score and red scale represents negative sentiment score.

## Results
[Sentiment Analysis for Donald J. Trump](http://18.237.90.86:5000/realdonaldtrump)
[Users followed by Donald J. Trump](http://18.237.90.86:5000/following/realdonaldtrump)



