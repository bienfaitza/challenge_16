# Amazon Vine Analysis

> Analyzing Amazon reviews written by members of the paid Amazon Vine program https://www.amazon.com/gp/vine/help.

## Objective

Like the majority of shoppers, Amazon's shoppers depend on product reviews to make a purchase decisions. Amazon makes their vine review datasets publicly available https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt. Vine reviews are quite large and can exceed the capacity of local machines to handle; hence, we are using Spark and AWS.

 
 

### ETL Process in Big Data using PySpark

Create DataFrames to match production-ready tables from two big Amazon customer review datasets.
Amazon_Reviews_ETL.ipynb

### Statistical Analysis 
Analyze whether reviews from Amazon's Vine program are trustworthy and free of bias.
Vine_Review_Analysis.ipynb
