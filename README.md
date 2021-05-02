# Making Big Data with Alexa
Based on Amazon's datasets, let's make data analysis and visualization. This project is based on one dataset alone contains over 1.5 million rows; with over 40 datasets.

Use the furnished schemata to create tables in your RDS database.

#  The procedure

- Two separate ZEPL notebooks and extract the list one into each notebook.
- Work with S3 data sources in two separate ZEPL notebooks.
- For each notebook (one dataset per notebook), we can:

   -- Count the number of records (rows) in the dataset.
   -- Transform the dataset to fit the tables in the schema file.
   -- RDS instance. 

Articulate the differents components of the Hadoop Ecosystem.
Run MapReduce hobs
Use Spark DataFrames to process large datasets, to make queries from Hadoop Distributed Files.

However do not forget that Big Data is reserve to large companies, we are talking about huge problems.

<Visualizations & Analytics + Computations + Storage + Distribution & Data Warehouse>

Hadoop fundamentals
MapReduce: Support for paralel computation. Map splits the job and Reduce put togheter the results.
HDFS: Hadoop Distributed Files System
Spark: Performs queries in the HDFS

# Issues you are going to find with extremely large dataset

- A place to store massive amounts of data
- A way to access data quicly
- A backup for hardware failure
- Ways to analyze data quickly

