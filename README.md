# Amazon_Vine_Analysis
## Overview:
The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.
In this project, I pick office product datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into PgAdmin. I will use PySpark to determine if there is any bias toward favorable reviews from Vine members in my dataset. Finally, I will write a summary of analysis for Jennifer to submit to the SellBy stakeholders.

## Results:
-22 reviews were from Amazon Vine members
-26987 reviews were not from Amazon Vine members
 
-There were 13 5 stars review from Amazon 22 Vine members.
-There were 14475 5 stars review from not Amazon 26987 Vine members.

-59% of review by Amazon Vine members were 5 stars
-53% of reviews by not Amazon Vine members were 5 stars.

## Summary:
This analysis shows there was no positivity bias for reviews in the paid Vine program with unpaid reviews, even though the 5 stars review percentage by Amazon Vine program members are a little bit higher. The additional analysis would be compare the 1 star review from both groups.



















