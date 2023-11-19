# Spotify-ETL

## Purpose
This data pipeline is designed to collect, process, and analyze Spotify data, utilizing various technologies for different stages of the pipeline. The workflow includes extracting data from a blob storage containing Spotify data, transforming it using Azure Databricks, orchestrating the pipeline with Azure Data Factory, and finally storing the processed data in a SQL database. The end goal is to enable seamless integration with Power BI for data visualization and analysis.

## Architecture
![Spotify Data Pipeline Architecture](<insert architecture image URL>)

## Data Flow
1. **Data Extraction:** Azure Data Factory extracts data from the blob storage containing Spotify data.
2. **Data Transformation:** Azure Databricks performs data transformation and enrichment tasks on the extracted Spotify data.
3. **Data Orchestration:** Azure Data Factory orchestrates the entire data pipeline, ensuring smooth transitions between stages.
4. **Data Storage:** Processed data is stored in Azure Data Lake Storage for flexibility and scalability.
5. **Data Loading:** Data is loaded from Data Lake Storage into a SQL database for structured storage and easy query access.
6. **Data Visualization:** Power BI connects to the SQL database, allowing for interactive and insightful data visualization.

## Technologies Used
- **Azure Data Factory:** Orchestrates and manages the data pipeline.
- **Azure Databricks:** Executes data transformation tasks efficiently.
- **Azure Data Lake Storage:** Serves as a scalable and flexible storage solution for processed data.
- **SQL Database:** Stores the structured data for easy query access.
- **Power BI:** Connects to the SQL database for data visualization.

## Data Model
The data model includes tables relevant to Spotify data, allowing for efficient analysis in Power BI. Specific entities may include track information, artist details, and user engagement metrics.

![Data Model](<insert data model image URL>)

## ETL Pipeline
The ETL pipeline consists of the following key tasks:
1. **Data Extraction:**
   - Extract data from the Spotify blob storage using Azure Data Factory.
2. **Data Transformation:**
   - Utilize Azure Databricks to perform necessary transformations on the Spotify data.
3. **Data Loading:**
   - Store the processed data in Azure Data Lake Storage for flexibility.
4. **Data Ingestion:**
   - Ingest data from Data Lake Storage to SQL Database for structured storage.
5. **Data Visualization:**
   - Connect Power BI to the SQL database for interactive data visualization.

![ETL Pipeline](<insert ETL pipeline image URL>)

## Development Setup
To set up and run the data pipeline locally, follow these steps:
- Provision necessary Azure resources, including Data Factory, Databricks, Data Lake Storage, and SQL Database.
- Configure connections and credentials for each component.
- Define required environment variables or configuration files.
- Execute the pipeline using Azure Data Factory triggers or manual execution.

## Code and Configurations
Provide code snippets, configuration files, and scripts for essential components such as Azure Data Factory pipelines, Azure Databricks notebooks, and SQL scripts. Make sure to remove or obfuscate sensitive information.

```python
# Sample code snippet or configuration example
# (your code here)
