## Amazon_Vine_Analysis
Module 16: Big Data

# Overview of the analysis

In this Big Data evaluation, we will be using natural language processing, applying ecosystems including Hadoop, Vs, MapReduce and Spark. Their application will be done by utilizing AWS, GoogleCollab and SQL. 

In our project, we will be working for Big Market, a marketing start-up The application of these tools will be done so to help determine if there is a bias reviews based on the Vine program. The product that has been selected is Reviews for Amazon Toys. 


# Results
The data set used for this analysis was Amazon reviews for Toys. The reviews are obtained from customers that have either been paid or not to publish a review on the product that they have purchased. In our case, the total number of 5-star reviews were 30414. However after analysing the reviews we obtained that the percentage of 5-star reviews for paid reviews was ~48% and that the percentage of 5-star reviews for unpaid reviews was ~48%. In this particular case we use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, we used PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. Given the results we observed that there is not bias, both the unpaid and paid review scored roughly the same. 

# Summary
There is no sufficient evidence to conclude that there is a positivity bias for reviews in the Vine program given the numbers above. Given that the score of paid and unpaid was the same, we can assume that the reviewers could have been honest about their experience with the product, however more analysis should be done. One additional analysis that could do with the dataset to support is to evaluate reviews different than those of 5 stars to get a better picture of the general publics view.


