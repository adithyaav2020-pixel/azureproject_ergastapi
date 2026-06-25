Formula 1 Drivers Data Analytics using Azure

Project Overview

This project is an end-to-end Azure Data Engineering solution developed to ingest, transform, analyze, and visualize Formula 1 drivers data. Data is extracted from the OpenF1 API, stored in Azure Data Lake Storage Gen2, transformed using Azure Databricks, and visualized through Power BI dashboards.

The entire workflow is automated using Azure Data Factory, ensuring seamless data movement and processing with minimal manual intervention.

Architecture

OpenF1 API
↓
Azure Data Factory (Automation & Orchestration)
↓
Azure Data Lake Storage Gen2 (Raw Layer)
↓
Azure Databricks (Data Transformation)
↓
Azure Data Lake Storage Gen2 (Presentation Layer)
↓
Power BI Dashboard

Technologies Used

- Azure Data Factory
- Azure Data Lake Storage Gen2
- Azure Databricks
- Apache Spark
- Delta Lake
- Power BI
- OpenF1 API
- Git & GitHub

Project Workflow

1. Automated Data Ingestion

- Azure Data Factory connects to the OpenF1 API.
- Driver data is automatically extracted and loaded into Azure Data Lake Storage Gen2.
- Pipelines can be scheduled to run automatically.

2. Data Storage

- Raw driver data is stored in the Raw Layer.
- Data is maintained for further processing and auditing.

3. Automated Data Transformation

- Azure Data Factory triggers Azure Databricks notebooks.
- Databricks cleans, transforms, and structures the driver data.
- Processed datasets are stored in the presentation layer.

4. Reporting and Visualization

- Power BI connects to the transformed datasets.
- Interactive dashboards provide insights into Formula 1 drivers and teams.

Automation Features

- Automated API Data Extraction
- Automated Data Lake Loading
- Automated Databricks Notebook Execution
- End-to-End Pipeline Orchestration
- Reduced Manual Processing
- Scalable Cloud-Based Architecture

Key Insights

- Total Drivers
- Drivers by Team
- Team-wise Driver Distribution
- Driver Information Analysis
- Interactive Dashboard Reporting

Repository Structure

F1-Drivers-Analytics/

├── README.md

├── architecture.png

├── notebooks/

├── screenshots/

└── documentation/

Future Enhancements

- Real-Time Data Ingestion
- Historical Driver Trend Analysis
- Machine Learning-Based Predictions
- Advanced Driver Performance Analytics

configuration Required
storage_account = "<storage_account_name>"
access_key = "<storage_account_key>"


Author

Adithya A V

Azure Data Engineering Project
