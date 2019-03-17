# WeRateDogs

The project aimed to analyze the data in <a href = 'https://twitter.com/dog_rates'>"WeRateDogs"</a> channel on Twitter.com.<br>

## Gathering Data
First, we gather data from different sources:

- *.csv file, stored in the local machine. This file contains preliminarily gathered data of tweets specified by a tweeet_id parameter. The file should be assessed, cleaned and structured in a desired manner.
- *tsv file stored in the remote server. This file contains the data about breed prediction based on pictures gathered from tweets in the channel. Each tweet specified by the tweet_id parameter. The file needs to be assessed, cleaned and structured in the desired way.
- Twitter API - an archive of all tweets in the channel. We need to get additional information from the Twitter server. Since we have the tweet_id parameter in both files mentioned above, we going to extract particular data, associated with each tweet_id from the server.

## Assess and Clean Data
We have three different sources of data and we need to get one solid data set with good quality and tidy data. Perform assessing data from each source and fix every issue we found to get data ready for analysis.

## Analysis
- Whether or not retweet count depends on the breed? If yes - what the top three breeds in retweets?
- Whether or not favorite count depends on the breed? If yes - what the top three breeds in favorites?
- Is there most popular dog names and what are they if exist?
- Still on the air

## Technologies
- Python
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Twitter API
- Regex
- Json
