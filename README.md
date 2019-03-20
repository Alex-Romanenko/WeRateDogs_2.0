# WeRateDogs

The project aimed to analyze the data in <a href = 'https://twitter.com/dog_rates'>"WeRateDogs"</a> channel on Twitter.com<br>

## Gathering Data
First, we gather data from different sources:

- *.csv file, stored in the local machine. This file contains preliminarily gathered data of tweets specified by a tweeet_id parameter. The file should be assessed, cleaned and structured in a desired manner.
- *tsv file stored in the remote server. This file contains the data about breed prediction based on pictures gathered from tweets in the channel. Each tweet specified by the tweet_id parameter. The file needs to be assessed, cleaned and structured in the desired way.
- Twitter API - an archive of all tweets in the channel. We need to get additional information from the Twitter server. Since we have the tweet_id parameter in both files mentioned above, we going to extract particular data, associated with each tweet_id from the server.

## Assess and Clean Data
We have three different sources of data and we need to get one solid data set with good quality and tidy data. Perform assessing data from each source and fix Quality and Tidiness issues we found to get data ready for analysis.

## Storing Data

After "assess and clean" stage we suppose to have a few different data frames with data associated with tweet_id. Plan to merge all data frames into one. Restructure final df if it needs and stores to the csv file.

## Analysis

We want to get answers to the following questions:

- What are the top three breeds holding most retweets?
- What are the top three breeds holding favorites?
- Are the breeds mentioned above are the same that holding most audience engagement (the sum of retweets and favorites)
- How often is the top breed holding most engagement (in the following mention just 'top breed') mentioned in tweets?
- What is the set of words for tweets with the top breed?
- How often the words from the top-breed-set appeared in tweets?
- Are there some words, that more specific for the top breed?
- We have a huuuge amount of other questions and gonna find their answers in other projects))

## Technologies
- Python
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Twitter API
- Regex
- Json
