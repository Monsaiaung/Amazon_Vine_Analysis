# Amazon_Vine_Analysis

## Overview of the Analysis

The purpose of this analysis is to check if there is any bias towards reviews that were written as part of the Vine program. The task will analyze if a paid Vine review makes a difference in the percentage of 5-star reviews. The technology/tools used in this analysis are AWS, Postgres, and PySpark in Google Colab. The dataset chosen to do the analysis is the video games dataset on S3 found at (https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt) 

## Results: Using bulleted lists and images of DataFrames as support, address the following questions:
### How many Vine reviews and non-Vine reviews were there?
![Vine and non-vine](https://github.com/Monsaiaung/Amazon_Vine_Analysis/blob/c930913df1e837537f66f47c4555baf7611becb7/Resources/1.png)

Vine Reviews: 94
Non-Vine Reviews: 40471

### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
![5 stars](https://github.com/Monsaiaung/Amazon_Vine_Analysis/blob/c930913df1e837537f66f47c4555baf7611becb7/Resources/five%20stars.png)

Vine reviews with 5 stars: 48
Non-Vone reviews with 5 stars: 15663

### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
![percentage](https://github.com/Monsaiaung/Amazon_Vine_Analysis/blob/c930913df1e837537f66f47c4555baf7611becb7/Resources/percent.png)

Vine Reviews with 5 stars percentage: 51.1%
Non-Vine Reviews with 5 stars percentage: 38.7%

## Summary: In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.

- From observation the analysis, it shows that the paid reviews makes up a small percentage of the total number of Reviews. Paid review count is 94 while Unpaid review count is 40471. The number of Paid reviews with 5 stars is 48 while Unpaid reviews with 5 stars is 15663. However when the percentage of paid review with 5 stars and unpaid review with 5 stars it shows that paid review with 5 stars has 51.1% while Unpaid review with 5 stars has 38.7%. This can be concluded that there might be some bias. Although to make a proper statement of biases more analysis shoud be tested. 
