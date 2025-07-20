# Serverless Data Lake Day – AWS Hands-On Project

This project is part of the **Serverless Data Lake Day** workshop from AWS Workshop Studio.  
It demonstrates how to build a serverless, scalable, and cost-effective data lake architecture using:

- Amazon Kinesis Data Firehose
- Amazon S3
- AWS Glue Crawlers & Jobs
- Amazon Athena  

---

## 🧪 Labs Completed

### ✅ Lab 1: Data Ingestion & Storage
- Ingested streaming or batch data using **Kinesis Firehose** into Amazon S3
- Verified file delivery in S3 bucket

📸 `kinesis-setup`  
📸 `s3-bucket`

---

### ✅ Lab 2: Data Cataloging and ETL
- Created **AWS Glue Crawler** to catalog S3 data
- Used **Glue Studio visual editor** to create an ETL Job
- Transformed and stored data back into S3

📸 `crawler-setup`  
📸 `data-catalog`  
📸 `glue-job-visual`  
📸 `job-run-success`

---

### ✅ Lab 3: Data Analytics (No Visualization)
- Queried processed datasets using **Amazon Athena**
- Performed SQL analytics over large-scale public data (GDELT)

📸 `athena-query`  
📸 `athena-result`

---

## 📚 What I Learned
- How to build a modular data lake pipeline using serverless AWS services
- The role of Glue Crawlers and Athena in data discovery and analysis
- Benefits of not provisioning a single server

---

## 🧼 Clean-up Notes
All AWS resources were cleaned up to avoid future charges.  

---

## 🔗 Workshop Link
[Serverless Data Lake Day – AWS Workshop Studio](https://catalog.us-east-1.prod.workshops.aws/workshops/ea7ddf16-5e0a-4ec7-b54e-5cadf3028b78/en-US)
