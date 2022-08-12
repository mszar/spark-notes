# Spark Basics

## Creating a SparkSession

SparkSession is the entry point to programming Spark with the Dataset and DataFrame API.
The builder can also be used to create a new session:

```scala
val spark = SparkSession.builder
     .master("local")
     .appName("App Name")
     .config("spark.some.config.option", "some-value")
     .getOrCreate()
```

After creating session we can read data from various sources:




#### sources:
* https://spark.apache.org/docs/3.2.0/api/java/org/apache/spark/sql/SparkSession.html