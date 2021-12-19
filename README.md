# Amazon_Vine_Analysis
## Overview
Analysis on Amazon Vine program to determine possible bias toward positive reviews from vine members

## Source
Amazon Review Datasets

## Tools
* Google Colab Notebook, 
* PostgreSQL, 
* pgAdmin 4, 
* Amazon Web Service AWS
* PySpark 


Performed ETL process to extract the dataset, transform data, connect to an AWS RDS instance, load the transformed 
data into pgAdmin and calculate different metrics. 

## Summary
51% of the reviews in the Vine program were 5 stars, while the percentage in the non-Vine reviews is as low as 39%, showing a favorable bias toward reviews in the Vine program.
