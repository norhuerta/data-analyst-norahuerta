# Data Analytic Platform (DAP) for the Vancouver Call Center

## Project Description
The Data Analytic Platform (DAP) for the Vancouver Call Center is a two-phase project aimed at enhancing the operational efficiency and safeguarding the data integrity of the city’s call center services. This project leverages advanced data analytics, cloud infrastructure, and AWS tools to improve service delivery, transparency, and compliance with data governance regulations.
## Objetive
### **Phase 1**: Call Handling Efficiency and Performance
In the first phase of the DAP, the primary goal was to improve call handling efficiency by analyzing operational metrics like call volume, average handling time, and service levels. By implementing a robust data pipeline using AWS services such as S3 for storage and AWS Glue for ETL processes, we processed call center metrics data (e.g., calls offered, calls handled). The descriptive metric introduced was the Call Handling Percentage, used to evaluate how efficiently the call center manages incoming calls, providing insights for resource planning and performance improvements​.
### **Phase 2**: Data Governance, Protection, and Monitoring
The second phase of the project focuses on safeguarding call center data while ensuring compliance with data governance and protection regulations​.This phase builds on the technical foundation laid in Phase 1 by integrating AWS's Well-Architected Framework, particularly focusing on the five pillars of operational excellence, security, reliability, performance efficiency, and cost optimization.
## Background
Vancouver’s City Call Center has faced challenges in managing the fluctuating volumes of calls efficiently while maintaining a high standard of service. The existing system struggles with delays and inconsistent handling times, impacting customer satisfaction negatively.
## Dataset
1. **Call Center Operational Data**
   - **dataset Name:** 3-1-1 Contact Center Metrics
   - **Source:** City of Vancouver’s open data portal.
   - **Details:** Includes metrics such as total calls offered, calls handled, calls abandoned, average speed of answer, and service levels for the years 2023 and 2024  
2. **Call Handling Performance Data**
   - **dataset Name:** callsGeneral.xls 
   - **Source:** AWS S3 (Landing, Raw, Curated zones). 
   - **Details:** Contains information such as the total number of calls offered, abandoned calls, and service level data​(DAP_CallCenter_Part_1).   
3. **Handled Calls Data**
   - **dataset Name:** callsHandled.xls
   - **Source:** AWS S3
   - **Details:** Focuses specifically on handled calls, tracking successful interactions between call agents and customers.
4. **Sensitive Data Detection Logs**
   - **dataset Name:** AWS Glue ETL Data (callsGeneral raw)
   - **Source:** AWS Glue 
   - **Details:** Includes logs for sensitive data detection, such as PII, from call center records.


## Methodology
### 1. Data 

### 2. Data 






