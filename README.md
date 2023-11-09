# aws-product-review-analysis
Data engineering - data streaming pipeline - real time - AWS Lambda, DMS, Kinesis, RDS, Redshift, EMR, DynamoDB

### AWS Services Used:
- Amazon API Gateway: To receive requests.
- AWS Lambda: To process API requests.
- Amazon Aurora (PostgreSQL): To store the main database.
- AWS Database Migration Service (DMS): For migrating and streaming data to Kinesis.
- Amazon Kinesis Data Streams: For real-time data streaming.
- Amazon S3: To store data in Parquet format.
- Amazon EMR (Elastic MapReduce): For processing Parquet files.
- Amazon Redshift: To store the final data warehouse.

### Architecture
![Logo](https://github.com/jamilvilela/aws-sentiment-analysis/blob/master/AWS-product-review-project-architecture.png)
