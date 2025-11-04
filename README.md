# sql-data-warehouse-project-
Welcome to the Data Warehouse and Analytics Project repository! 
This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a portfolio project, it highlights industry best practices in data engineering and analytics.
# Data Architecture
The data architecture for this project follows Medallion Architecture Bronze, Silver, and Gold layers:
<img width="1200" height="691" alt="Data-Engineer-portfolio-High Level Architecture drawio" src="https://github.com/user-attachments/assets/45dd5205-9f98-4555-a7be-649392608161" />

Bronze Layer: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
Silver Layer: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
Gold Layer: Houses business-ready data modeled into a star schema required for reporting and analytics.
 
