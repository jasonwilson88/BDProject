## How to use Docker

### 1 install docker

// docker login

### 2 pull image

```
docker pull maxjin/5540projectjupyter:2  //image name is maxjin/5540projectjupyter and tag is 2
// Linux
docker run -p 8888:8888 -v `pwd`:/home/jovyan/work --name spark jupyter/pyspark-notebook 
// Win10
docker run -p 8888:8888 -v /c/Users/Max/docker/jupyter:/home/jovyan/work --name spark maxjin/5540projectjupyter:2
// And just use jupyter notebook in localhost like usual.
// You should put your dataset under `/c/Users/Max/docker/jupyter` or `pwd` (depend on OS)
// And load data part should be `XX = spark.read.json("/home/jovyan/work/tweets.json")`
docker exec -it spark bash // Linux bash, not important
```

### There are some .ipynb created by me, you can upload your local file(.ipynb) and use your local dataset and then get the results, all done
