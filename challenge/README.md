# Amazon_Vine_Analysis
## Overview
In this project, I had access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. I picked one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. The data link is: https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Wireless_v1_00.tsv.gz
Next, I used PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. 

## Results
According to the results 
- There are 613 total number of paid reviews and 64968 unpaid reviews
https://mermaidzhang-databootcamp-bucket.s3.ca-central-1.amazonaws.com/Totalreviews.png
- There are 222 5 star reviews among paid users and 30543 5-star reviews among uppaid users
https://mermaidzhang-databootcamp-bucket.s3.ca-central-1.amazonaws.com/Total5Star.png
- the rate for five star reviews among paid users are 36% while it is 47% among non-paid users
https://mermaidzhang-databootcamp-bucket.s3.ca-central-1.amazonaws.com/TotalPercent.png
## Summary 
Positivity bias may denote three phenomena: a tendency for people to report positive views of reality; a tendency to hold positive expectations, views, and memories; and a tendency to favor positive information in reasoning.Based on results, people who are non-paid users have actaully higher percentage to give 5-star reviews indicate there is no significant positive bias for vine users. Otherwise, there would be significant higher numbers among paid users compared to non-paid users. 

It is also suggested to look at different demographic breaks of the data to learn about different atittudes for gender, and age group. If the differences are non-significant, we could accept our hypythesis for all people.
