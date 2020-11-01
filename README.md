# TESTING PYSPARK MLLIB IN A CLASSIFICATION PROBLEM

Spark is a framework for parallel data processing used for developing big data applications and solving some problems that Hadoop have. For example, one of the main problems with Hadoop is speed, especially when a lot of disk read and write operations had to be done.

In addition, Spark incorporates very powerful libraries for data analysis. For example, MLLib, which is a library for Machine Learning, GraphX, which allows working with graphs. There is also Spark Streaming, to work in real time. It’s important to know that the typical data structure in PySpark is called RDD (Resilent Distributed Dataset) that determine the way in which Spark (and PySpark) works.

 ![alt text](https://github.com/qgvidal/pysparkmllib/blob/main/images/pysparkml1.png)

But let’s focus on Spark MLlib. Spark MLlib is Spark's Machine Learning library. It is a very powerful library with a large number of algorithms. Some of them we have already studied. It incorporates regression algorithms (like LinearRegressionWithSGD, DecissionTree regressor, GradientBoostedTrees), classification (like LogisticRegressionWithSGD, LogisticRegressionWithBFGS, DecisionTree, GradientBoostingTrees…), clustering (like Kmeans, StreamingKMeans…), and selection of linear recommendation systems or extraction of features.

