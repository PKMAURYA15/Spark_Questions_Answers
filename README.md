# Spark_Questions_Answers
Here we have added different types of spark questions and their answers



How do we create RDDs in Spark?
Spark provides two methods to create RDD:

1. By parallelizing a collection in your Driver program.

2. This makes use of SparkContext’s ‘parallelize’

1
2
3
method val DataArray = Array(2,4,6,8,10)
 
val DataRDD = sc.parallelize(DataArray)
3. By loading an external dataset from external storage like HDFS, HBase, shared file system.



