# AWS Infrastructure for DAP Call Center

## 1. Data Protection: IAM and KMS
- **IAM Roles**: Created IAM roles to restrict access to the S3 bucket storing call center data. This ensures that only authorized users and applications can access the data.
- **KMS Encryption**: All data stored in the S3 bucket is encrypted using AWS Key Management Service (KMS).

## 2. Data Governance: AWS Glue
- **ETL Jobs**: Used AWS Glue to create ETL jobs that transform raw call center data into a usable format.
- **PII Detection**: Implemented PII detection using AWS Glue DataBrew to ensure that no sensitive information (e.g., names, addresses) is exposed.

## 3. Data Monitoring: CloudWatch
- **CloudWatch Alarms**: Set up alarms to monitor AWS billing.
  For example:
   ![example](/images/Dolares35.png),
   an alert is triggered if estimated costs exceed a predefined threshold ($35). This ensures cost control and timely notifications.
