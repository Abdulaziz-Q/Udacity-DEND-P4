# Udacity-DEND-P4

### Project: Data Lake
A music streaming startup, Sparkify, has grown their user base and song database even more and want to move their data warehouse to a data lake. 
Their data resides in S3, in a directory of JSON logs on user activity on the app, as well as a directory with JSON metadata on the songs in their app.

As their data engineer, I'm tasked with building an ETL pipeline that extracts their data from S3, processes them using Spark, 
and loads the data back into S3 as a set of dimensional tables. This will allow their analytics team to continue finding insights in what songs their users are listening to.

### Project Description
In this project, I'll apply what I've learned on Spark and data lakes to build an ETL pipeline for a data lake hosted on S3. I will need to load data from S3, 
process the data into analytics tables using Spark, and load them back into S3. I'll deploy this Spark process on a cluster using AWS.

### Project Datasets
I'll be working with two datasets that reside in S3. Here are the S3 links for each:

- Song data: s3://udacity-dend/song_data
- Log data: s3://udacity-dend/log_data

### Projects files

- **etl.py** reads data from S3, processes that data using Spark, and writes them back to S3
- **dl.cfg** contains my AWS credentials
