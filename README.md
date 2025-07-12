# ETL-pipeline
Architecture Overview
This pipeline includes the following stages:

Data Ingestion

Service: Azure Data Factory

Purpose: Ingests data from various sources like HTTP endpoints, APIs, databases, etc.

Raw Data Storage

Service: Azure Data Lake Storage Gen2

Purpose: Stores unprocessed/raw data in its native format.

Data Transformation

Service: Azure Databricks

Purpose: Processes and transforms raw data into a clean, analytical-ready form.

Processed Data Storage

Service: Azure Data Lake Storage Gen2

Purpose: Stores transformed and curated data.

Data Serving Layer

Service: Azure Synapse Analytics

Purpose: Enables fast querying and aggregation of transformed data.

Reporting & Visualization

Service: Microsoft Power BI

Purpose: Creates dashboards and visual reports for business insights.

