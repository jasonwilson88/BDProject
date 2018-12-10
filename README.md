# BDProject

Part 1:

Tweets were collected in json format using the python code found in Part1/Collection. This code was found at https://stackoverflow.com/questions/45940984/python-twitter-stream-save-to-file

Hashtags and urls were extracted from the tweets using Apache Spark with both python and scala on different collections of tweets

Apache Hadoop and Apache Spark(python) hashtag/url word counts were run on the same data set where 'data' was the key term. Pyspark extraction and wordcount code is found under SparkWordCount/python. The log files for these runs can be found under logs/HadoopAndSparkPython	
	
Apache Spark hashtag/url word counts were also run in scala on a different set of collected tweets where 'data' was also the key term. The extraction/wordcount code and log files for these runs can be found under SparkWordCount/scala
		
Output for all three runs can be found in the output subdirectories 

Part 2:

Queries using Apache Spark on Twitter data with the keyword beer. Queries include:

1. Top brands by social media presence (tweet count, followers count, and favourites count)

2. Cities that tweet the most about beer

3. Beer tweet counts by date

4. Top beer brands by locality (USA vs Other)

5. Top favorited accounts that tweet about beer

6. Multimedia beer tweets

7. Top languages used in beer tweets besides English

8. Top mentioned beer brands

9. Beer tweet counts by hour 

10. Distribution of tweets considered 'possibly sensitive'
