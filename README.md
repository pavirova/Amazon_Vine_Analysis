# Amazon_Vine_Analysis

## Overview 
This analysis consisted of using PySpark along with Google Collab and Amazon Web Services(AWS) to perform an ETL on a music dataset where we extract, transform and connect the data to an AWS RDS instance to load the transformed data into a PGAdmin database where we can then use PySpark to perform calculations on Amazon Vine music reviews.

## Results

- How many Vine reviews and non-Vine reviews were there?

![Resources/totalreviews.png](Resources/totalreviews.png)

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

![Resources/5starreviews.png](Resources/5starreviews.png)

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

![Resources/percentreviews.png](Resources/percentreviews.png)

## Summary

As can be seen from the percentage of 5 star reviews above, the percentage of Vine 5 star reviews is 0, whereas the percentage of non-vine reviews is 63.7%, meaning there is no positivity bias for reviews in the Vine program. Another analysis that can be done with the dataset is to use the describe() method to look at the summary statistics of the dataset to further analyze the mean, min, max, and standard deviation of the music reviews.
