# Hive-Case-Study-

Problem Statement
With online sales gaining popularity, tech companies are exploring ways to improve their sales by analysing customer behaviour and gaining insights about product trends. Furthermore, the websites make it easier for customers to find the products they require without much scavenging. Needless to say, the role of big data analysts is among the most sought-after job profiles of this decade. Therefore, as part of this assignment, we will be challenging you, as a big data analyst, to extract data and gather insights from a real-life data set of an e-commerce company.

One of the most popular use cases of Big Data is in eCommerce companies such as Amazon or Flipkart. So before we get into the details of the dataset, let us understand how eCommerce companies make use of these concepts to give customers product recommendations. This is done by tracking your clicks on their website and searching for patterns within them. This kind of data is called a clickstream data.

The clickstream data contains all the logs as to how you navigated through the website. It also contains other details such as time spent on every page, etc. From this, they make use of data ingesting frameworks such as Apache Kafka or AWS Kinesis in order to store it in frameworks such as Hadoop. From there, machine learning engineers or business analysts use this data to derive valuable insights. 

For this assignment, you will be working with a public clickstream dataset of a cosmetics store. Using this dataset, your job is to extract valuable insights which generally data engineers come up within an e-retail company.

The implementation phase can be divided into the following parts:

Copying the data set into the HDFS:

Launch an EMR cluster that utilizes the Hive services, and

Move the data from the S3 bucket into the HDFS 

Creating the database and launching Hive queries on your EMR cluster:

Create the structure of your database, 

Use optimized techniques to run your queries as efficiently as possible

Show the improvement of the performance after using optimization on any single query.

Run Hive queries to answer the questions given below.

Cleaning up
Drop your database, and
Terminate your cluster 

You are required to provide answers to the questions given below.

Find the total revenue generated due to purchases made in October.

Write a query to yield the total sum of purchases per month in a single output. 

Write a query to find the change in revenue generated due to purchases from October to November.

Find distinct categories of products. Categories with null category code can be ignored.

Find the total number of products available under each category.

Which brand had the maximum sales in October and November combined?

Which brands increased their sales from October to November?

Your company wants to reward the top 10 users of its website with a Golden Customer plan. Write a query to generate a list of top 10 users who spend the most.
