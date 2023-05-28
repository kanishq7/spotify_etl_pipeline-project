# Spotfiy Data Pipeline End-To-End Python Data Engineering Project

### Description
In this Project, we will build an ETL(EXTRACT,TRANSFORM,LOAD) pipeline using the Spotify API on AWS.
Implement Complete Data Pipeline Data Engineering Project using Spotify

### Overview
* Integrating with Spotify API and extracting Data
* Deploying code on AWS Lambda for Data Extraction
* Adding trigger to run the extraction automatically
* Writing transformation function
* Building automated trigger on transformation function
* Store files on S3 properly
* Building Analytics Tables on data files using Glue and Athena

### Architecture

![Architecture Diagram](https://github.com/kanishq7/spotify_etl_pipeline-project/blob/main/spotify.png)


### Services Used
1) **s3 or (Simple Storage Services) :** Amazon S3 bucket is used to retrieve or store information (data) through data types with the help of Application Programming Interface calls.

2) **AWS Lambda :** Lambda function procures all the necessary information from the API gateway and runs the back-end codes. It provides a quick update whenever there is a new upload to the Amazon S3 bucket.It is a computing service that runs the code in response to events and automatically manages the computing resources.

3) **CloudWatch:** It is used to create different metrics. It provides monitoring for resources and applications.

4) **Glue Crawaler and Data Catalog :** AWS Glue is a fully managed extract, transform and load (ETL) tool that automates the time-consuming data preparation process for consequent data analysis.
 AWS Glue automatically detects and catalogs data with AWS Glue Data Catalog, recommends and generates Python or Scala code for source data transformation, provides flexible scheduled exploration, and transforms and loads jobs based on time or events in a fully managed, scalable Apache Spark environment for data loading in a data target. 

5) **Amazon Athenna :** Amazon Athena is a cost-effective, interactive query service that makes it easy to analyze data in Amazon Simple Storage Service (Amazon S3) with standard ANSI-SQL.Amazon Athena is serverless, so there’s no infrastructure or clusters to purchase, manage or maintain. Because it uses Amazon S3 as the underlying data store, Amazon Athena is highly available and durable with data redundantly stored across multiple facilities and multiple devices in each facility.

