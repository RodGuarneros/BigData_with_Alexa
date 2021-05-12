# Making Big Data with Alexa
Based on Amazon's datasets, let's make data analysis and visualization. This project is based on two datasets with over 9 million (wireless products opinions)  and 2 million (video games opinios).

Use the furnished schemata to create tables in your RDS database.

#  The procedure

- Two separate ZEPL notebooks and extract the list one into each notebook.
- Work with S3 data sources in two separate ZEPL notebooks.
- For each notebook (one dataset per notebook), we can:

   - Count the number of records (rows) in the dataset.
   - Transform the dataset to fit the tables in the schema file.
   - RDS instance. 

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
- A way to access data quickly
- A backup for hardware failure
- Ways to analyze data quickly

# Analysis

93% of consumers cite electronic product and service reviews as a determining factor in their purchase. Amazon, to avoid fake reviews (#fakereviews) created Amazon Vine to send trusted reviewers products for their opinion (#star_rating). But: How skewed are these opinions from those they receive massively from their users? Does Vine work to reveal opinion bias?

I invite you to know the results of this Big Data Analysis for a total of 1,785,997 opinions on 65,787 video games, and 9,002,021 opinions for 143,250 wireless products and accessories sold by the platform. This analysis confirms the bias that exists between the ratings provided by users and the ratings certified by the Amazon Vine program.
Indeed, what we call “Regular Opinions” in this analysis can include biased reviews that start from false and optimistic opinions that raise the #star_rating of the products and concentrating them on 4.5 and 5 stars.

![wireless.jpg](https://github.com/RodGuarneros/BigData_with_Alexa/blob/main/Resources/regular_opinions_guarneros.png)
 
In contrast to the distribution of reviews made by Vine Costumers for the same products, where you can see a higher variance and a lower average star_rating.

 ![vine.jpg](https://github.com/RodGuarneros/BigData_with_Alexa/blob/main/Resources/Vine_Opinions_Guarneros.png)

The foregoing is consistent with the analyzes performed in relation to electronic reviews, where product evaluations have been found to drop when "questionable" electronic reviews are removed.

From an analysis carried out by The Washington Post newspaper, it was found that 60% of the electronic reviews carried out on the Amazon platform can be "questionable" (they come from users whose social networks do not have followers, the comments are very similar in all purchased products, etc.).
In this sense, the Amazon Vine program is extremely valuable for setting up periodic reviews like the one presented here and exposing the valuation and bias that “questionable” electronic reviews can cause in your purchasing decisions.

Next time, I suggest you rate your purchases with more than the reference of the stars and the information provided in the comments of other buyers. Ultimately, remember that you can always return the product.

