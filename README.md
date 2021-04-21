# Amazon_Vine_Analysis


## Project Overview
Using Amazon's camera review dataset, an ETL process is performed by first extracting the data from Amazon's S3 database. Next, PySpark was then further used to transform the data and connect to the Amazon's Web Service RDS instance. Lastly, The transformed data is then loaded to pgAdmin. The goal for this analysis is to determine if there is any bias toward favourable reviews from Vine members in the dataset used. 


## Resources
-Data Source: amazon_reviews_us_Camera_v1_00.tsv.gz

-Software: Jupyter Notebook 6.2.0. PostgreSQL 13.2, Amazon Web Services (AWS)


## Results
-There are 607 total Vine reviews and another 50522 None-Vine reviews

-There are 257 Vine reviews that are 5-stars and another 25220 None-Vine reviews that are 5-stars

-There is about 42% of Vine reviews that are 5-stars and another 50% of the None-Vine reviews are 5-stars


## Summary
Based off of the percentages of 5-star between Vine and None-Vine reviews, it is showing that there is no positivity bias towards Vine reviews considering that None-Vine has 50% 5-star compared to 42% to Vine reviews. Another analysis could be performed by inspecting the different star reviews and checking its percentages. By introducing 3-star reviews and up for example, there would be better accuracy towards the analysis since a greater population ins reviewed. Lastly, a reverse analysis could also be performed. Instead of looking at positive reviews, an analysis by looking at negative reviews between both Vine and None-Vine users could be performed.  
