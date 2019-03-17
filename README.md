# WeRateDogs

The project aimed to analyze the data in <a href = 'https://twitter.com/dog_rates'>"WeRateDogs"</a> channel on Twitter.com.<br>
- We have an archive of all tweets posted before 2017-08-01. <br>
Stored in file <a href = 'https://s3.amazonaws.com/video.udacity-data.com/topher/2018/November/5bf60fbf_twitter-archive-enhanced/twitter-archive-enhanced.csv'>twitter-archive-enhanced.csv</a>
- We have a data of the breed of the dog prediction, came out from pictures in WeRateDogs channel and prediction model provided in course resources. <br>
Stored in file <a href = 'https://s3.amazonaws.com/video.udacity-data.com/topher/2018/November/5bf60fe7_image-predictions/image-predictions.tsv'> image-predictions.tsv</a>

The first part of project named **"Twitter Archive"** is for assessing and cleaning data in the archive of tweets to prepare for analysis.<br><br>

The second part named **"Twitter API"** - is for getting additional data from source using Twitter API. Connecting to the channel through API, pull the data, subtract necessary part of it and store in specific file.<br><br>

The third part **"Breed Prediction"** is for connecting two data sets and analyze its data. Probably, pull more necessary data from the source.<br><br>

The fours part is for final complex analysis with visualization

## Technologies
- Python
- Pandas
- Numpy
- Matplotlib
- Twitter API
- Json
