# Data Analytic Platform (DAP) for the Vancouver Call Center

## Project Overview
This project focuses on designing and implementing a Data Analytic Platform (DAP) for the City of Vancouver’s Call Center. The main objectives are:
1. Improve **Call Handling Percentage** through effective data monitoring.
2. Migrate the current system to **AWS** while ensuring data protection, governance, and monitoring using various AWS services.
3. Implement **Data Wrangling** to clean and prepare raw call center data for further analysis and decision-making.

## Project Phases
### **Phase 1**: Data Wrangling and Preparation
- **Objective**: Prepare call center data by cleaning and transforming it for ingestion into AWS.
- **Key Tools**: 
  - AWS Glue DataBrew for data cleaning
  - AWS S3 for data storage
  - Python (Pandas) for additional data wrangling
  - AWS Glue for Extract, Transform, Load (ETL)
  
### **Phase 2**: AWS Infrastructure Design and Implementation
- **Objective**: Build and manage the infrastructure needed for the DAP, including data protection, governance, monitoring, and cost optimization.
- **Key AWS Services**: 
  - **Amazon S3** for storage of raw and processed data.
  - **AWS Glue** for ETL processes.
  - **CloudWatch** for data monitoring, tracking alarms, and cost monitoring.
  - **IAM** and **KMS** for identity management and encryption.
