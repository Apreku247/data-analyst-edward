UCW HR Data Analytics Platform: Descriptive Analysis (Project Part 1)
![Alt Text](https://github.com/Apreku247/data-analyst-edward/blob/a5c15689406feba505b227e3b7c4c391ee39187e/image.png)

Project Description
This project involves a descriptive analysis of UCW's HR data using AWS cloud services. The goal is to summarize key insights from employee data, policy details, and departmental inquiries to support workforce planning and decision-making.

Project Title
UCW HR DAP: Workforce and Policy Analysis

Objective
Conduct a descriptive analysis to uncover patterns, trends, and insights from HR datasets, enabling data-driven decisions.

Dataset

- Employees-List: Employee records with application dates and program details.
  
- Policy-List: Program names, positions, and durations.

- Department-List: Financial inquiries, payment amounts, and application data.

Methodology

- Data Collection: Ingested data from EC2 to S3 using PowerShell.
  
- Data Profiling: Used AWS Glue DataBrew for structure and quality assessment.
  
- Data Cleaning: Corrected null values, duplicates, and column errors.
  
- Cataloging: Created tables using AWS Glue Data Catalog.
  
- Visualization: Generated charts and graphs for insights using DataBrew.

Insights and Findings

- Popular programs had significantly higher applications.
  
- Application peaks aligned with academic cycles.
  
- Financially active departments showed higher payment volumes.
  
- Program length anomalies suggested data entry issues.

Recommendations

- Standardize program durations.

- Allocate HR resources during peak periods.

- Provide additional support to high-activity departments.

- Maintain data consistency with validation checks.

Tools and Technologies

- AWS EC2 & S3: Data storage and ingestion
- AWS Glue DataBrew: Profiling, cleaning, visualization
- AWS Glue Data Catalog: Metadata management
- AWS Athena: SQL querying

PowerShell: Data transfer automation

Deliverables

- Cleaned datasets in CSV and Parquet formats.

- AWS Glue Catalog tables.

- Visual reports using Glue DataBrew.

Summary insights and actionable recommendations.

Standardize Program Durations:

  - Address inconsistencies in program lengths by reviewing and adjusting them to align with standard durations.
  
Optimize HR Resource Allocation:

  - Allocate additional HR resources during peak application periods to manage increased workloads efficiently.
  
Support High-Activity Departments:
  - Provide targeted financial and administrative support to departments with consistently high inquiry volumes.
  
Enhance Data Quality Management:

  - Implement automated validation checks to detect and correct data entry errors, ensuring reliable data for future analysis.


