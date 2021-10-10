# Data_pipelines

Datapipelines is a simple repository that follows the code examples from the O'Reilly book Data Pipelines Pocket Reference.

I will be following the code examples from each chapter:
1. `extract_mysql_full.py` extracts the data from an AWS MySQL database, creating a CSV file with the data, and the uploading the file to an S3 bucket.

### Database
Create a MySQL database either locally or on AWS RDS. Set the config values for environment variables prefixed with `MySQL_` in `pipeline.conf`.

### S3
Create an AWS S3 bucket. Set the config values for environment variables prefixed with `AWS_` in `pipeline.conf`.
