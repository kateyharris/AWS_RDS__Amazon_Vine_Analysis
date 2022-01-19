# Amazon_Vine_Analysis

## Overview
Analyze Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

In this project there are approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. Using the major appliances datasets and PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, using PySpark, to determine if there is any bias toward favorable reviews from Vine members in the dataset. 

## Results

- **Deliverable 1: Perform ETL on Amazon Product Reviews**
- ![Snap6](https://user-images.githubusercontent.com/90797036/150045987-0398b142-bedc-4321-b882-528acc0c1d34.png)

- **Deliverable 2: Determine Bias of Vine Reviews**
![Snap14](https://user-images.githubusercontent.com/90797036/150045833-a9183fba-7990-4644-aaa8-b8db3c7e95b5.png)

## Summary
51% of the reviews in the Amazon Vine program were 5 star reviews. 
39% of the the non-Amazon-Vine reviews were 5 star reviews. 
There is a positivity bias for reviews in the Amazon Vine program.
