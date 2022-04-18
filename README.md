# amazon_vine

## Overview of the analysis
Analyzing Amazon reviews written by members of the paid Amazon Vine program to determine if there is any bias toward favorable reviews from Vine members in the selected dataset.

## Result

Customer table

![pgAdmin_customers_table](https://github.com/Krystal313/amazon_vine/blob/3e546a639bfb281e804d145353c9d2bee3e5061a/Resources/pgAdmin_customers_table.png)

Product table

![pgAdmin_products_table](https://github.com/Krystal313/amazon_vine/blob/3e546a639bfb281e804d145353c9d2bee3e5061a/Resources/pgAdmin_products_table.png)

Review ID table

![pgAdmin_review_id_table](https://github.com/Krystal313/amazon_vine/blob/3e546a639bfb281e804d145353c9d2bee3e5061a/Resources/pgAdmin_review_id_table.png)

Vine table

![pgAdmin_Vine_table](https://github.com/Krystal313/amazon_vine/blob/3e546a639bfb281e804d145353c9d2bee3e5061a/Resources/pgAdmin_Vine_table.png)


- How many Vine reviews and non-Vine reviews were there?
  There are 21 vine reviews and 7689 non-vine reviews.
  
- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
  There are 11 vine reviews were 5 stars and 4444 non-vine reviews were 5 stars. 
  
- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
  The percentage of vine review that were 5 stars is 0.14% and non-Vine reviews is 57.64%
  
## Summary
From this analysis, we can consult that there is no bias among the 5 stars reviews given the percentage of non vine review is 57.64%. To have better determination whether there is a bias within the program, we can also analysis other product categories given this particular analysis was done on jewelery.
