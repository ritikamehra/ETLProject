# ETLProject

## Goal:
To build ETL pipeline including the following tasks:
1. Extracting the transactional data from a given MySQL RDS server to HDFS(EC2) instance using Sqoop.
2. Transforming the transactional data according to the given target schema using PySpark. 
3. This transformed data is to be loaded to an S3 bucket.
4. Creating the Redshift tables according to the given schema.
5. Loading the data from Amazon S3 to Redshift tables.
6. Performing the analysis queries.

## Data Dictionary:
https://cdn.upgrad.com/uploads/production/513e0220-322c-4842-b305-1248da32315d/ETL+Project+-+RDS+Data+dictionary.pdf

## Analysis Queries
1. Top 10 ATMs where most transactions are in the ’inactive’ state
2. Number of ATM failures corresponding to the different weather conditions recorded at the time of the transactions
3. Top 10 ATMs with the most number of transactions throughout the year
4. Number of overall ATM transactions going inactive per month for each month
5. Top 10 ATMs with the highest total amount withdrawn throughout the year
6. Number of failed ATM transactions across various card types
7. Top 10 records with the number of transactions ordered by the ATM_number, ATM_manufacturer, location, weekend_flag and then total_transaction_count, on weekdays and on weekends throughout the year
8. Most active day in each ATMs from location "Vejgaard"
