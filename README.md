# Data_pipelines

Datapipelines is a simple repository that follows the code examples from the O'Reilly's book Data Pipelines Pocket Reference.

I will be following the code examples from each chapter:
1. `extract_mysql_full.py` extracts the data from a MySQL instance database from AWS RDS, creating a CSV file with the data, and then uploading the file back to AWS in an S3 bucket.

### Database
Create a MySQL database either locally or on AWS RDS. Set the config values for environment variables prefixed with `MySQL_` in `pipeline.conf`.

### S3
Create an AWS S3 bucket. Set the config values for environment variables prefixed with `AWS_` in `pipeline.conf`.
