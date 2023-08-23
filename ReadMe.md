# MapReduce Based CNN

## For HandWritten Digit Recognition

In this project, we propose a novel approach to accelerate the training process of a CNN for handwritten digit recognition using the MapReduce paradigm. MapReduce is a distributed computing framework that allows for the parallelization of tasks across multiple nodes in a cluster, thus offering the potential for significant speedup in computation. We programmed a <b>CNN model from scratch</b> using only Map and Reduce operation to experiment with distributed computing using PySpark.

## How to run

### Databricks

> We reccommend using databricks community edition (it is free) to run this notebook.\

### Local

> Otherwise, to run locally, follow the following steps\
> install python and use 'pip install pyspark' to load pyspark module\
> Before running the notebook, add this piece of code to it in the beginning\
> from pyspark.sql import SparkSession\
> spark = SparkSession.builder.appName("LocalApp").getOrCreate()\
> conf = SparkConf().setAppName("LocalApp")\
> sc = SparkContext(conf=conf)
