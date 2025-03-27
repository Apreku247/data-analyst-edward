# data-analyst-edward
UCW HR Data Analytics Platform: Descriptive Analysis (Project Part 1)
Project Description
This descriptive analysis project focuses on the foundational HR datasets used in the University Canada West (UCW) Data Analytics Platform (DAP). Through this analysis, we aim to summarize key characteristics of employee data, policy information, and departmental inquiries. The goal is to generate actionable insights for workforce planning, policy management, and financial analysis.
Project Title
UCW HR DAP: Foundational Workforce and Policy Dataset Analysis
Objective
The primary objective of this project is to conduct a descriptive analysis of three HR datasets to uncover trends, data patterns, and insights. This analysis will support data-driven decision-making for UCW's human resources management.
Dataset
The analysis utilizes three datasets containing HR-related information:
Employees-List.csv: Contains employee records, application dates, and program associations.
Policy-List.csv: Details HR policies, program names, and program lengths.
Department-List.csv: Tracks departmental financial inquiries, including payments and applications.
These datasets are relational, with foreign keys linking Employees-List to Policy-List via ProgramID, and Department-List to Employees-List via ApplicationID.
Methodology

1. Data Collection and Preparation
The datasets were ingested using AWS EC2 and uploaded to an S3 bucket (ucw-hr-data-edward).
PowerShell scripts were used for the data transfer.
Initial data cleaning steps addressed missing values, duplicate records, and column name issues (e.g., correcting PrgramLength to ProgramLength).
2. Descriptive Statistics
Summary statistics were calculated using AWS Athena for key variables, including:
Total number of employees
Number of unique programs
Total and average payment amounts
Additional insights were generated using Glue DataBrew.
3. Data Visualization
Visualizations were created using AWS Glue DataBrew to illustrate findings:
Bar Charts representing program participation trends.
Pie Charts visualizing payment distribution across departments.
Line Graphs showing application trends over time.
4. Workforce Segmentation
Employees were segmented by application behavior and department to identify workforce patterns.
Departments with high inquiry volumes were highlighted for further analysis.
Insights and Findings

The following insights were drawn from the descriptive analysis:
Program Participation Patterns: Popular programs had significantly higher applications.
Application Timeline Trends: Peak application periods aligned with the beginning of academic terms.
Program Length Trends: Most programs were 6 or 12 months, but outliers suggested potential irregularities.
Departmental Inquiries: Financially active departments showed higher payment volumes.
Data Quality Improvements: Standardized datasets improved reliability and analysis accuracy.
Recommendations

Based on the findings, the following recommendations are proposed:
Review Program Lengths: Address anomalies by consolidating program durations.
Leverage Peak Periods: Allocate HR resources during identified high-application periods.
Support High-Activity Departments: Evaluate additional HR or financial support for departments with frequent inquiries.
Ensure Data Consistency: Implement ongoing data validation checks.
Expand Metadata Management: Maintain up-to-date Glue Data Catalog entries for enhanced data governance.
Tools and Technologies

Tool	Purpose
AWS EC2	Data staging and script execution
AWS S3	Data storage
AWS Glue DataBrew	Data profiling and visualization
AWS Glue Data Catalog	Metadata management
AWS Glue Crawler	Schema inference and table creation
AWS Athena	SQL querying and analysis
PowerShell	Data transfer and management

Deliverables
Cleaned datasets in CSV and Parquet formats.
AWS Glue Catalog tables with searchable metadata.
Summary reports generated via Athena queries.
Visualizations for HR analysis using Glue DataBrew.
This descriptive analysis report.
This report provides a comprehensive understanding of UCW’s HR data, empowering data-driven decision-making for workforce planning, policy evaluation, and financial management. If further analysis is required, including diagnostic or predictive modeling, this cleaned dataset is ready for advanced exploration.
