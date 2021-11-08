# Amazon_Vine_Analysis

## Overview of the analysis
The objective of this analysis is to review all Pet Products reviews in the Amazon Vine Program from members. PySpark was used to perform ETL on the dataset and load the data in pgAdmin. PySpark was also used to determine if there is any bias bias toward favorable reviews from Vine members in the dataset.

## Results

- There are 170 paid reviews and 37840 unpaid reviews.
- There are 65 paid 5 star reviews and 20612 unpaid 5 star reviews.
- There are 38% 5 star paid reviews and 54.5% 5 star unpaid reviews.

## Summary: 
The paid 5 star reviews are lesser than unpaid 5 star reviews. There is no bias in the reviews in the Vine program. 
NLP analysis could be carried out on the review body to identify key words such as "unhappy", "upset", "broken", "shipment issue" etc to see if the reviews which were unpaid used more of those metric words than paid words
