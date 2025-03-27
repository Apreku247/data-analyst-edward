UCW HR Data Analytics Platform: Descriptive Analysis (Project Part 1)
![Alt Text](https://github.com/Apreku247/data-analyst-edward/blob/20d41157a9cb51b946fcaa6b7afe6e7ff72199b9/image.png)
![Alt Text](https://github.com/Apreku247/data-analyst-edward/blob/6fc399a1b64e97510ba3e43c45bf2b8900167404/image.png)
![Alt Text](https://github.com/Apreku247/data-analyst-edward/blob/1efe749b387f632f37e0773f31e5085d61e002a0/image.png)

Project Description
This project analyzes HR data from University Canada West (UCW) to gain insights into employee applications, program durations, and departmental financial activities. By examining patterns and trends using AWS cloud services, the goal is to identify areas for improvement in workforce planning, resource allocation, and data management. The findings from this analysis will support UCW in making informed decisions to optimize HR operations and enhance overall efficiency.

Project Title
UCW HR DAP: Workforce and Policy Analysis

Objective
The primary objectives of this descriptive analysis are:
 - To document the end-to-end procedure for ingesting, preparing, and cataloging the Employees-List, Policy-List, and Department-List datasets using AWS cloud services. This process ensures a streamlined and transparent workflow for HR data management.
   
 - To profile and understand the datasets’ structure, content, quality, and statistical characteristics. This analysis will provide insights into employee application trends, policy structures, and department-level financial activities.
   
 - To generate descriptive summaries and visualizations that illustrate key HR metrics and patterns, supporting evidence-based decision-making at UCW.
   
 - To ensure these foundational datasets are cleaned, well-documented via the AWS Glue Data Catalog, and readily available for integration into more complex analyses within UCW's HR Data Analytics Platform (DAP).

Dataset

- Employees-List: Employee records with application dates and program details.
  
- Policy-List: Program names, positions, and durations.

- Department-List: Financial inquiries, payment amounts, and application data.

Methodology

- Data Collection: Ingested data from EC2 to S3 using PowerShell.
- 
![Alt Text](https://github.com/Apreku247/data-analyst-edward/blob/3b360976194350651a8d731e5df70df5c94e9685/image.png)
![Alt Text](https://github.com/Apreku247/data-analyst-edward/blob/317616d2997ba27257f20c1d25d771adbffa921b/image.png)
![Alt Text](https://github.com/Apreku247/data-analyst-edward/blob/cdfe750805af6c086f95b4fa4e25b331dbfcaf8c/image.png)
![Alt Text](https://github.com/Apreku247/data-analyst-edward/blob/3736fb70f5fd4c33590eda439c5b081bc9acb6ac/image.png)
![Alt Text](https://github.com/Apreku247/data-analyst-edward/blob/b8864bf91e149e1c4a95911f59646ce5684041e3/image.png)
 
- Data Profiling: Used AWS Glue DataBrew for structure and quality assessment.
-
![Alt Text](https://github.com/Apreku247/data-analyst-edward/blob/b0cd36a03fd272fc9ee0236ed828176a9d647240/image.png)
  
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

Summary insights 
This descriptive analysis of UCW's HR data revealed trends in employee applications, program durations, and departmental financial activities. Key findings include high application volumes in certain programs, application peaks during academic cycles, and increased financial inquiries from specific departments. To address these insights, it is recommended to standardize program durations, allocate resources effectively during peak periods, provide additional support to high-activity departments, and implement automated data validation to enhance data quality and ensure informed decision-making.

Recommendations.

Standardize Program Durations:

  - Address inconsistencies in program lengths by reviewing and adjusting them to align with standard durations.
  
Optimize HR Resource Allocation:

  - Allocate additional HR resources during peak application periods to manage increased workloads efficiently.
  
Support High-Activity Departments:
  - Provide targeted financial and administrative support to departments with consistently high inquiry volumes.
  
Enhance Data Quality Management:

  - Implement automated validation checks to detect and correct data entry errors, ensuring reliable data for future analysis.

  - Course completion badge
![Alt Text](https://github.com/Apreku247/data-analyst-edward/blob/78b5b29e8b6e592f671d3c12a17c65197d3e0e23/AWS_Academy_Graduate___AWS_Academy_Cloud_Foundations_Badge20250327-26-286s31.pdf)

