# Amazon_Vine_Analysis

An analysis of Amazon product reviews from the Amazon Vine program.

## Data Citation
The dataset used in this analysis is the Digital Video Game Reviews dataset. 🔗 "https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Digital_Video_Games_v1_00.tsv.gz"

## Overview
* The purpose of this analysis was to use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Then use PySpark to determine if there is any bias toward favorable reviews from Vine members in the Digital Video Game Reviews dataset.

The tables were successfully loaded into pgAdmin

![Table1](https://github.com/vvinci21/Amazon_Vine_Analysis/blob/764644e5cbe5794ce20f0cf0121b25d6ca287f39/pic_1.png)
![Table2](https://github.com/vvinci21/Amazon_Vine_Analysis/blob/764644e5cbe5794ce20f0cf0121b25d6ca287f39/pic_2.png)
![Table3](https://github.com/vvinci21/Amazon_Vine_Analysis/blob/764644e5cbe5794ce20f0cf0121b25d6ca287f39/pic_3.png)
![Table4](https://github.com/vvinci21/Amazon_Vine_Analysis/blob/764644e5cbe5794ce20f0cf0121b25d6ca287f39/pic_4.png)


## Results
![results](https://github.com/vvinci21/Amazon_Vine_Analysis/blob/b70455cba40908c55bf9ec45a710436b87079de2/reviews1.png)

The above results show paid number of reviews, paid 5 star reviews, paid 5 star perecentage, unpaid number of reviews and unpaid 5 star reviews.

## Summary
* Based on the results paid 5 star reviews make up almost 50% of all paid reviews. However, with only 48 total paid 5 star reviews and over 15,000 unpaid 5 star reviews I would determine it has little bias on the overall review of the products.
* Determining duplicate reviews from the same reviewer could remove some bias data either for or against a game. 
