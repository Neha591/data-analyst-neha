# data-analyst-neha
# Project 1 City of Vancouver
# 1. Project Title:Data Wrangling for Business Licenses of Animal Services – City of Vancouver
# Objective:
The primary goal of this project is to clean, structure, and analyze business license data for animal services in Vancouver, ensuring high-quality data for insights and regulatory compliance. Specifically, we aim to:
- Identify inconsistencies in the dataset
- Perform quality checks (completeness, uniqueness, freshness)
- Transform semi-structured data into a structured format
- Enable meaningful analysis for business and regulatory purposes
# Background:
Vancouver City boasts a list of animal service businesses, such as pet groomers, veterinary clinics, pet stores, and other related businesses. The data is publicly available but with missing values, inconsistencies, and duplicate entries that must be resolved to have proper insight.
Through data wrangling, we aim to refine the dataset for better analysis, policy development, and business intelligence related to animal service regulations in Vancouver.
# Dataset:
The dataset includes:
- Business Name
- License Number
- Business Type (Veterinary, Pet Store, Grooming, etc.)
- Issue and Expiry Dates
- Business Status (Active, Inactive, Suspended)
- Location Data (Address, Postal Code, Neighborhood)
- Possible issues include missing values, inconsistent formatting, and outdated records that need to be addressed during data processing.
# Methodology:
The data wrangling process involves several key steps:
- Data Ingestion – Raw dataset is uploaded to AWS S3 for cloud processing
- Data Profiling – Using AWS Glue DataBrew to assess schema, missing values, and anomalies
- Data Cleaning – Handling missing data, removing duplicates, and standardizing formats
- Data Transformation – Converting semi-structured to relational format using AWS Glue
- Data Quality Control – Ensuring completeness, uniqueness, and data freshness
- Exploratory Data Analysis (EDA) – Understanding trends in business licenses
- Data Storage & Security – Storing structured data in AWS S3 with encryption (KMS)
# Tools and Technologies:
- Cloud Storage: AWS S3
- Data Processing: AWS Glue, AWS Glue DataBrew
- Data Querying: Amazon Athena (SQL-based querying)
- Security & Governance: AWS KMS (encryption), AWS IAM (access control)
- Monitoring: AWS CloudWatch & AWS CloudTrail
# Deliverables:
- Cleaned and structured dataset stored in AWS S3
- Data Quality Report summarizing completeness, uniqueness, and freshness
- Exploratory Analysis Report for business licensing trends
- Automated pipeline for continuous data quality monitoring
# Timeline:
- Week 1: Data collection & profiling
- Week 2: Data cleaning & transformation
-  Week 3: Data quality checks & governance setup
-  Week 4: Exploratory analysis & final reporting

# 2. Data Quality Control for City of Vancouver – Business Licenses for Animal Services
Project Description:This project ensures the accuracy, completeness, and reliability of business license data related to animal services in Vancouver. We improve data integrity, reduce inconsistencies, and ensure business regulation compliance through the implementation of data quality control techniques.
# Project Title: Data Quality Control for Business Licenses of Animal Services – City of Vancouver
# Objective:
The main objective is to assess and improve the quality of business license data by:
- Identification and correction of missing, inconsistent, and duplicate records
- Verification of data completeness, uniqueness, and freshness
- Confirmation that business license records are compliant with regulations
- Enhancing data usability for analytical reports and insights
# Background:
The City of Vancouver maintains a business license database for animal service businesses (veterinary clinics, pet stores, groomers, etc.). Raw data is riddled with errors, duplicates, and old records that can lead to inaccurate business insights.
Without quality control, businesses can operate with the incorrect licenses, expired registrations will not be identified, and analytical reports may be incorrect. This project ensures that the dataset is credible and reliable for analysis and governance.
# Scope:
The scope of this project is:
- Data Profiling: Error identification, duplicates, and missing values
- Data Cleaning: Inconsistencies removal and missing fields filling
- Validation Checks: Data validation against business rules and regulations
- Data Storage: Saving good-quality data in AWS S3 for future examination
- Data Monitoring: Setting alerts for anomalies and security threats
# Methodology:
The data quality control process follows these steps:
- Data Ingestion & Profiling:
- Upload raw dataset to AWS S3
- Use AWS Glue DataBrew for schema validation and error detection
# Data Cleaning & Validation:
- Remove duplicate business license entries
- Standardize formats (license numbers, business names, addresses)
- Handle missing values through imputation or deletion
# Data Quality Checks:
- Completeness: Ensure all required fields are populated
- Uniqueness: Detect and remove duplicate business records
- Freshness: Verify that license renewal dates are up-to-date
# Data Governance & Security:
- Encrypt data using AWS Key Management Service (KMS)
- Apply AWS IAM policies for controlled access
# Data Monitoring & Automation:
- Set up AWS CloudWatch alerts for unusual data changes
- Use AWS CloudTrail for auditing modifications
# Deliverables:
- Cleaned and validated business license dataset stored in AWS S3
- Data Quality Report summarizing key findings and improvements
- Automated quality checks for real-time data validation
- Monitoring system for ongoing data integrity
# Timeline:
- Week 1: Data profiling and schema validation
- Week 2: Data cleaning and validation checks
- Week 3: Implementation of governance and security measures
- Week 4: Setting up monitoring alerts and generating final reports

# 3. Exploratory Data Analysis (EDA) for City of Vancouver – Business Licenses for Animal Services
# Project Description:
Here in this project, we perform Exploratory Data Analysis (EDA) of Vancouver business license data for animal services. With the help of trends, patterns, and insights analysis, we attempt to understand the distribution, growth, and compliance of businesses operating in this sector.
# Project Title:
Exploratory Data Analysis (EDA) for Business Licenses of Animal Services – City of Vancouver
# Objective:
The primary goal is to uncover insights into business licensing trends by:
- Understanding how many businesses are active, inactive, or new
- Analyzing growth patterns over the years
- Identifying geographical distribution of businesses across Vancouver
- Detecting common business categories (e.g., veterinary clinics, pet stores, groomers)
- Spotting potential data quality issues through outlier detection
# Dataset:
The dataset consists of business license records from the City of Vancouver’s Open Data Portal. It includes:
- Business Name & Type – Identifies the nature of the business (e.g., pet shop, vet clinic)
- License Status – Active, inactive, expired, or pending licenses
- Issue & Expiry Dates – Helps analyze business growth trends
- Geolocation Data – Pinpoints where businesses are concentrated
- Revenue/Employee Count (if available) – Provides insights into business scale
# Methodology:
The EDA process includes the following key steps:
## Data Collection & Preprocessing:
- Load business license data from AWS S3
- Convert semi-structured data into relational format using AWS Glue
- Remove duplicates and missing values
## Descriptive Analysis:
- Calculate total number of active vs. inactive businesses
- Analyze the trend of new business registrations over the years
- Identify the most common business categories
## Geospatial Analysis:
- Visualize business distribution across Vancouver neighborhoods
- Identify high-density areas for animal services
## Outlier & Anomaly Detection:
- Detect unusually high or low business activity
- Spot inconsistencies in license renewals
## Data Visualization & Reporting:
- Use Amazon QuickSight & Matplotlib/Seaborn for visual analysis
- Generate interactive dashboards and reports
# Tools and Technologies:
- AWS S3 – Data storage
- AWS Glue – Data transformation
- Amazon Athena – Querying the dataset
- Pandas, NumPy – Data manipulation
- Seaborn, Matplotlib – Data visualization
- Amazon QuickSight – Dashboard and reporting
# Deliverables:
- Exploratory Data Analysis Report summarizing key findings
- Visual dashboards displaying business trends and insights
- Geospatial maps of business distribution
- Recommendations based on observed patterns

# Project 2 University Canada West Policies (HR Department)
# 1. Project Description: UCW Company – HR Data Wrangling
# Project Title:
"HR Data Wrangling and Quality Control for UCW Company Using AWS Cloud Services"
# Objective:
The goal of the project is to collect, clean, convert, and organize HR-related data (employee roster, professional qualifications, financial assistance) for optimal data quality and usability. The project utilizes AWS cloud computing for automated data ingestion, data conversion, data security, and governance. 
# Background:
Human Resource (HR) departments handle a lot of employee data, including personal data, professional credentials, and financial data. Raw HR data is marred with inconsistencies, missing values, and unstructured data and is not analyzable. This project focuses on data wrangling for cleaning and structuring HR datasets so that correct conclusions and decision-making can be ensured.
# Dataset:
- The dataset contains HR-related records in the form of CSV files in AWS S3.
- Employee List: Employee ID, Name, Department, Designation, Joining Date, Salary.
- Professional Skills: Employee ID, Skills, Certifications, Experience Level.
- Finance Support: Employee ID, Salary, Bonuses, Allowances, Deductions.
# Methodology:
This project follows a structured ETL (Extract, Transform, Load) pipeline using AWS cloud services:
## Data Collection & Ingestion:
- Upload HR datasets to AWS S3 storage.
- Use EC2 instances for data ingestion and initial validation.
## Data Profiling & Cleaning:
- Identify missing values, duplicates, and inconsistent formats.
- Standardize data (e.g., date formats, salary structures, skill categories).
- Data Transformation & Cataloging:
- Use AWS Glue to clean and transform HR data.
- Structure the data into well-defined schemas in AWS S3.
## Data Validation & Quality Control:
- Implement automated quality checks to monitor data consistency.
- Encrypt sensitive HR data using AWS KMS (Key Management Service).
## Data Governance & Monitoring:
- Track data access and modifications using AWS CloudWatch & CloudTrail.
- Implement policies to ensure compliance with HR data privacy standards.
# Tools and Technologies:
- AWS S3 – Data Storage
- AWS EC2 – Data Processing
- AWS Glue – Data Cleaning & Transformation
- Amazon Athena – SQL-based Querying & Reporting
- AWS KMS – Data Encryption & Security
- AWS CloudWatch & CloudTrail – Monitoring & Governance
# Deliverables:
- Cleaned and structured HR dataset stored in AWS S3.
- AWS Glue Data Catalog for HR data management.
- Data security measures using AWS KMS encryption.
- Automated data monitoring with AWS CloudWatch & CloudTrail.
- Reports on employee skills, salaries, and finance trends using Amazon Athena.
# Timeline:
Phase Task Duration
- Week 1-2 Data Collection & Ingestion 
- Week 3 Data Cleaning & Profiling 
- Week 4 Data Transformation & Storage 
- Week 5 Data Security Implementation 
- Week 6 Data Governance & Monitoring Setup 
- Week 7-8 Testing & Final Deployment

# 2. Project Description: Data Quality Control for UCW HR Data
# Project Title:
"Ensuring Data Quality Control for UCW HR Data Using AWS Cloud Services"
# Objective:
The purpose of this project is to preserve the accuracy, consistency, and reliability of HR data for datasets by using quality controls. Data validation, cleaning, transformation, security, and regular monitoring by means of AWS cloud services would mean that.
# Background:
HR data plays a critical role in workforce planning, skill analysis, and financial planning. However, it becomes unreliable due to errors like repeated entries, data values missing, inconsistent formatting, and security hazards. To maintain data integrity, automated quality management processes that capture and correct flaws before analysis must be employed. 
# Scope:
The scope of this project consists of data quality control for HR data sets stored in AWS S3, comprising:
- Employee List: Ensuring accurate employee records (IDs, names, designations, salaries).
- Professional Skills: Validating skill certifications, experience levels, and missing entries.
- Finance Support: Ensuring correct salary calculations, bonuses, and deductions.
- Implementing data security and governance policies to protect sensitive HR data.
# Methodology:
To achieve high data quality, the project follows these key steps:
## Data Validation & Profiling:
- Identify missing values, duplicates, and outliers in HR datasets.
- Use AWS Glue for automatic schema validation and data integrity checks.
## Data Cleaning & Transformation:
- Remove duplicates and standardize data formats.
- Implement data correction rules for employee details and salary structures.
## Data Security & Governance:
- Encrypt sensitive HR data using AWS KMS (Key Management Service).
- Define access control policies to restrict unauthorized data modifications.
## Automated Alerts & Monitoring:
- Utilize AWS CloudTrail & AWS CloudWatch to track changes in data & unauthorized access.
- Implement automated notification for data quality problems, operation failures, & security breaches.
## Automated Monitoring & Alerts:
- Use AWS CloudTrail & CloudWatch to track changes in data & unauthorized access.
- Enforce automatic data quality issue alerts, security issues, & operations failure.
# Deliverables:
- Cleaned and validated HR datasets in AWS S3.
- Data quality reports highlighting inconsistencies and corrections.
- Security measures (AWS KMS encryption, access control policies).
- Automated monitoring setup using AWS CloudWatch & CloudTrail.
- Improved data governance framework for UCW HR operations.
# Timeline:
- Week 1-2 Data Validation & Profiling 
- Week 3 Data Cleaning & Transformation 
- Week 4 Data Security Implementation 
- Week 5 Governance & Compliance Setup 
- Week 6 Monitoring & Alerts Configuration 
- Week 7-8 Testing & Final Deployment

# 3. Project Description: Descriptive Analysis of UCW HR Data
# Project Title:
"Descriptive Analysis of HR Data for UCW Using AWS Cloud Services"
# Objective:
The objective of this project is to use descriptive analytics techniques on HR data in an effort to summarize key trends, distributions, and patterns among employee demographics, professional competencies, and financial assistance. This will allow HR teams to make educated decisions on workforce planning, competency development, and compensation management.
# Dataset:
The analysis is done on HR data found in AWS S3, categorized into three groups:
- Employee List: Employee ID, Name, Age, Department, Designation, Joining Date, Salary.
- Professional Skills: Employee ID, Skills, Certifications, Experience Level.
# Methodology:
The project follows a structured approach to descriptive analysis:
## Data Collection & Cleaning:
- Ingesting HR datasets from AWS S3 and performing data cleaning (removing duplicates, handling missing values).
## Data Exploration & Summarization:
- Using AWS Athena to perform SQL queries for summary statistics (mean, median, mode, variance).
- Identifying workforce trends (age distribution, department-wise employee count, salary variations).
## Data Visualization:
- Generating bar charts, histograms, and pie charts for easy interpretation using Amazon QuickSight.
- Visualizing salary distribution, skill trends, and department-wise growth patterns.
## Key Insights & Reporting:
- Extracting insights such as average salary per department, most common skills, and salary growth trends.
- Preparing automated dashboards for HR decision-makers.
# Tools and Technologies:
- AWS S3 – Data Storage
- AWS Glue – Data Cleaning & Transformation
- Amazon Athena – SQL-based Querying & Analysis
- Amazon QuickSight – Data Visualization & Reporting
- AWS CloudWatch – Monitoring and Performance Tracking
# Deliverables:
- Cleaned HR dataset ready for analysis.
- Summary statistics on employee demographics, salaries, and skills.
- Data visualization dashboards in Amazon QuickSight.
- HR insights report for workforce planning.
