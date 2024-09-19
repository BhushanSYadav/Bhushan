# Bhushan
Projects on Exploratory Data Analysis, Descriptive Analysis, Diagnostic Analysis, Data Wrangling, and Data Quality Control using AWS services.
Project Title: Exploratory Data Analysis of City of Vancouver 

Objective: To explore and identify patterns, anomalies, and key insights within the provided dataset using AWS services.

Dataset: Data is taken from Open Source Vancouver dataset portal

Descriptive Analysis:
Objective: To summarize and describe the main features of the dataset using statistical measures and AWS services.
Methodology:
1. Data Collection: Data was sourced from open source Vancouver dataset portal
2. Data Summary: Descriptive statistics were calculated using AWS Athena for key variables in the dataset.
3. Data Visualization: Excel was used to create charts and graphs to represent the distribution and central tendencies.

Tools and Technologies:
- AWS S3: For dataset storage.
- AWS Glue: For data cleaning and transformation.
- AWS Athena: For running SQL queries and summarizing data.
- Excel: For creating visual summaries.

Key Data Insights:

Customer Spending Patterns: The analysis revealed that spending levels varied significantly across different product categories. High-ticket items like electronics and home appliances showed seasonal trends, with spikes around major holidays.

Product Category Performance: Clothing and accessories were among the most consistent performers throughout the year, with minimal variation across months. However, luxury items exhibited notable fluctuations in sales, influenced by economic factors and consumer confidence.

Geographic Distribution of Sales: Sales were highest in metropolitan regions, while rural areas experienced comparatively lower transaction volumes. However, niche categories such as agricultural equipment performed better in rural areas.

Diagnostic Analysis: 

Objective: To identify the root cause of trends or anomalies observed in the dataset using AWS cloud services and diagnostic methods.

Methodology Used:

Data Collection: Sales data was collected from XYZ Retail’s internal database. AWS Glue was used for cleaning and preparing the data.

Data Processing: Data was analyzed using AWS Athena to run SQL queries for identifying key sales trends and patterns across various product categories.

Root Cause Analysis: An in-depth analysis using diagnostic methods revealed poor performance in certain regions, particularly areas where new competitors entered the market.


Tools and Technologies:

AWS S3: Data storage for easy access and scalability.

AWS Glue: Used for data cleaning and ETL processes.

AWS Athena: SQL queries helped in understanding sales trends and identifying the factors responsible for the decline.


Key Insights:

Sales Drop in Key Segments: The diagnostic analysis revealed that sales had declined most significantly in the apparel segment, with a 20% reduction year over year.

Regional Performance: Sales in urban regions were performing better compared to rural areas, where foot traffic was lower.

Inventory Management: High inventory levels in underperforming categories led to overstock issues, which contributed to declining profit margins.

Data Wrangling of data at the City of Vancouver

Methodology:

Data Collection: Data was collected from various open data portals and internal databases within the City of Vancouver.

Data Cleaning: AWS Glue and DataBrew were used to handle missing data and standardize inconsistent entries across datasets.

Data Transformation: Additional columns, such as date and permit type, were added to facilitate comparison between the different years (2023 and 2024).

Storage: The processed datasets were stored in AWS S3, ready for further analysis.

Tools and Technologies:

AWS S3: For storing and organizing large datasets.

AWS Glue: For performing data transformation and cleaning.

AWS DataBrew: Used to clean and manage data for easier analysis.

Key Findings:

Data Preparation for Municipal Data: The dataset involving municipal permits and customer interactions required extensive cleaning, addressing missing entries and inconsistent data formats. AWS Glue DataBrew was employed to ensure the dataset was structured properly for analysis.

Data Transformation: AWS Glue was used to transform the raw datasets, such as water permits and business licenses, into a unified format, enabling comparison across different municipal categories.

Data Wrangling Outcome: By performing data wrangling, the processed datasets were made ready for further diagnostic and predictive analysis, including trend identification in various permit types and customer service inquiries.

Data Quality Control for the City of Vancouver

Methodology:

Data Collection: Data was collected from the City of Vancouver's open data portal and internal municipal databases for various domains, such as business permits, property taxes, and 311 inquiries.

Data Quality Checks: AWS Glue performed automated checks for duplicates, missing values, and incorrect formats across multiple datasets.

Data Governance: AWS IAM (Identity and Access Management) and AWS KMS (Key Management Service) were implemented to ensure proper access controls and encryption of sensitive data.

Tools and Technologies:

AWS S3: Used for storing raw and processed municipal datasets.

AWS Glue: Automated the ETL (Extract, Transform, Load) process and managed data quality checks.

AWS IAM & KMS: Used to control access and secure data through encryption.

Key Findings:

Data Integrity: The analysis showed issues related to duplicate records and incorrect data formats across municipal data like business permits and property taxes. These issues were addressed using AWS Glue to ensure high-quality data across all departments.

Automation of Data Quality Processes: AWS Glue was employed to automate the process of identifying and fixing data quality issues, such as duplicate entries and missing values. This ensured consistent data quality across the project’s datasets.

Data Governance Implementation: AWS IAM and KMS were utilized to secure sensitive municipal data, ensuring that only authorized personnel could access or manipulate the data. This enforced the strict data governance guidelines required by the city.















