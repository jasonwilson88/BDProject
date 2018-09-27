# BDProject

Part 1:

Tweets were collected in json format using the python files found in Part1/Collection

Hashtags and urls were extracted from the tweets using Apache Spark with both python and scala on different collections of tweets

Apache Hadoop and Apache Spark(python) hashtag/url word counts were run on the same data set where 'data' was the key term. Pyspark extraction and wordcount code is found under SparkWordCount/python. The log files for these runs can be found under logs/HadoopAndSparkPython	
	
Apache Spark hashtag/url word counts were also run in scala on a different set of collected tweets where 'data' was also the key term. The extraction/wordcount code and log files for these runs can be found under SparkWordCount/scala
		
Output for all three runs can be found in the output subdirectories 
