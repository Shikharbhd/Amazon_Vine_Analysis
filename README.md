# Amazon_Vine_Analysis

## Overview of the Project:

This project analyzes Amazon Vine program and determines if there is a bias toward favorable reviews from Vine members.
The analysis uses PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin and calculate different metrics.
The analysis was focused on the US reviews for video games.

## Results

### 1. How many Vine reviews and non-Vine reviews were there?

There were 94 Vine reviews against a total of 40471 Non-vine reviews.

  a. Vine reviews. 

  ![5.Vinereviews.png](https://github.com/Shikharbhd/Amazon_Vine_Analysis/blob/main/Resources/Images/5.Vinereviews.png)


  b. Non-Vine reviews.

  ![6.nonVinereviews.png](https://github.com/Shikharbhd/Amazon_Vine_Analysis/blob/main/Resources/Images/6.nonVinereviews.png)

### 2. How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

There were 48 Five Stars Vine reviews against a total of 15663 Non-five Stars Vine reviews.

a. Vine reviews. 

![7.FiveStarPaid.png](https://github.com/Shikharbhd/Amazon_Vine_Analysis/blob/main/Resources/Images/7.FiveStarPaid.png)


b. Non-Vine reviews.

![8.FiveStarUnpaid.png](https://github.com/Shikharbhd/Amazon_Vine_Analysis/blob/main/Resources/Images/8.FiveStarUnpaid.png)

### 3. What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

51% of the reviews in the Vine program were 5 stars reviews whereas the percentage in the non-Vine reviews is only 39%.

a. Vine reviews. 

![9.FiveStarPaidPercent.png](https://github.com/Shikharbhd/Amazon_Vine_Analysis/blob/main/Resources/Images/9.FiveStarPaidPercent.png)


b. Non-Vine reviews.

![10.FiveStarUnpaidPercent.png](https://github.com/Shikharbhd/Amazon_Vine_Analysis/blob/main/Resources/Images/10.FiveStarUnpaidPercent.png)

## Summary
51% of the reviews in the Vine program were 5 stars reviews whereas the percentage in the non-Vine reviews is only 39%. This describes a positivity bias for reviews in the Vine program.

Additionally we could analyse the statistical distribution (mean, median and mode) of the star rating for the Vine and non-Vine reviews.
