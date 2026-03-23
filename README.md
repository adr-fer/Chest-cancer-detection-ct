# Chest-cancer-detection-ct
This project focuses on identifying the severity of patient encounters using healthcare data. To achieve this objective, key business questions will be addressed through a complete data science process that includes data cleaning, exploratory data analysis, KPI development, and machine learning modeling.

The project incorporates NLP techniques, as well as linear and logistic regression models applied to features derived from KPI processes and raw data analysis. Visualizations such as graphs, charts, and images will be used to support the conclusions, utilizing tools like Tableau and PowerPoint.

Tools & Technologies
- AWS S3 (data storage)
- AWS Glue (ETL processing)
- AWS Cloudwatch
- AWS Athena (SQL analysis)
- AWS SageMaker
- PySpark (data transformation)
- Python (modeling and analysis)
- Tableau (data visualization)
  
Data Pipeline Architecture
The data pipeline follows a structured workflow:
- Raw healthcare data is stored in AWS S3
- Data is cleaned and transformed using AWS Glue (PySpark)
- Cleaned data is stored in the curated S3 layer in Parquet format
- AWS Athena is used for querying, exploratory data analysis (EDA), and KPI development
- AWS SageMaker is used for building and evaluating machine learning models
- AWS CloudWatch is used to monitor job execution and logs
