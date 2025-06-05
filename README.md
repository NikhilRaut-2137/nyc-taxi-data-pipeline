# nyc-taxi-data-pipeline
A complete data engineering pipeline that ingests and processes NYC Green Taxi trip data using Azure Data Factory and Azure Databricks. The project demonstrates a modern Lakehouse architecture with structured layers (Bronze, Silver, Gold), scalable ETL pipelines, and cloud-native best practices



📦 Features

✅ Ingests monthly NYC Green Taxi .parquet files from public URL

✅ Stores raw data in Azure Data Lake (Bronze layer)

✅ Cleans and transforms data in Azure Databricks (Silver/Gold layers)

✅ Orchestrates the entire process using Azure Data Factory

✅ Connected to GitHub for version control of ADF artifacts

✅ Follows best practices for Lakehouse architecture



📂 Tech Stack

Azure Data Factory – ETL orchestration

Azure Data Lake Storage Gen2 – Data storage

Azure Databricks – Data processing with PySpark

Delta Lake – Transactional data format

Azure Blob Storage – File storage

GitHub – Version control



📊 Pipeline Structure

| Layer  | Description                         |
| ------ | ----------------------------------- |
| Bronze | Raw `.parquet` files ingested as-is |
| Silver | Cleaned and filtered data           |
| Gold   | Aggregated data ready for reporting |

