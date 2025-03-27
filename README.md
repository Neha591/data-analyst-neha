# data-analyst-neha
Project 2 City of vancouver
Project Title:Data Wrangling for Business Licenses of Animal Services – City of Vancouver

Objective:
The primary goal of this project is to clean, structure, and analyze business license data for animal services in Vancouver, ensuring high-quality data for insights and regulatory compliance. Specifically, we aim to:

Identify inconsistencies in the dataset

Perform quality checks (completeness, uniqueness, freshness)

Transform semi-structured data into a structured format
-Enable meaningful analysis for business and regulatory purposes

Background:
The City of Vancouver maintains a database of businesses that provide animal services, including pet grooming, veterinary clinics, pet stores, and other related businesses. This data is publicly available but often contains missing values, inconsistencies, and redundant entries that must be addressed for accurate insights.

Through data wrangling, we aim to refine the dataset for better analysis, policy development, and business intelligence related to animal service regulations in Vancouver.
Dataset:
The dataset includes:
📌- Business Name
📌 License Number
📌 Business Type (Veterinary, Pet Store, Grooming, etc.)
📌 Issue and Expiry Dates
📌 Business Status (Active, Inactive, Suspended)
📌 Location Data (Address, Postal Code, Neighborhood)

Possible issues include missing values, inconsistent formatting, and outdated records that need to be addressed during data processing.
Methodology:
The data wrangling process involves several key steps:

1️⃣ Data Ingestion – Raw dataset is uploaded to AWS S3 for cloud processing
2️⃣ Data Profiling – Using AWS Glue DataBrew to assess schema, missing values, and anomalies
3️⃣ Data Cleaning – Handling missing data, removing duplicates, and standardizing formats
4️⃣ Data Transformation – Converting semi-structured to relational format using AWS Glue
5️⃣ Data Quality Control – Ensuring completeness, uniqueness, and data freshness
6️⃣ Exploratory Data Analysis (EDA) – Understanding trends in business licenses
7️⃣ Data Storage & Security – Storing structured data in AWS S3 with encryption (KMS)
Tools and Technologies:
🔹 Cloud Storage: AWS S3
🔹 Data Processing: AWS Glue, AWS Glue DataBrew
🔹 Data Querying: Amazon Athena (SQL-based querying)
🔹 Security & Governance: AWS KMS (encryption), AWS IAM (access control)
🔹 Monitoring: AWS CloudWatch & AWS CloudTrail
Deliverables:
📌 Cleaned and structured dataset stored in AWS S3
📌 Data Quality Report summarizing completeness, uniqueness, and freshness
📌 Exploratory Analysis Report for business licensing trends
📌 Automated pipeline for continuous data quality monitoring
Timeline:
📆 Week 1: Data collection & profiling
📆 Week 2: Data cleaning & transformation
📆 Week 3: Data quality checks & governance setup
📆 Week 4: Exploratory analysis & final reporting


