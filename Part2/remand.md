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
docker exec -it spark bash // Linux bash
```

### There are some .ipynb created by me, you can upload your local file and use your local dataset and then get the results, all done
