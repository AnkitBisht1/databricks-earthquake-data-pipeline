# Earthquake Data Engineering Pipeline (Databricks)

## Project Overview
This project demonstrates an end-to-end Data Engineering pipeline built using Databricks to process earthquake data. The pipeline follows the Medallion Architecture (Bronze, Silver, Gold) to transform raw seismic data into structured datasets ready for analysis and reporting. The goal of the project is to automate earthquake data processing and provide reliable insights for research, risk assessment, and decision-making.

## Technologies Used
- Databricks
- Python / PySpark
- Delta Lake
- ETL Pipeline Development
- Medallion Architecture (Bronze, Silver, Gold)
- Databricks Workflows for Pipeline Orchestration

## Architecture
This project follows the Medallion Architecture which organizes data processing into three layers:

### Bronze Layer
- Ingests raw earthquake data from the source dataset.
- Stores raw data without transformation.
- Acts as the landing zone for incoming data.

### Silver Layer
- Cleans and transforms the raw data.
- Handles missing values and data standardization.
- Creates a structured dataset suitable for further processing.

### Gold Layer
- Performs aggregations and prepares curated datasets.
- Produces analytics-ready data for reporting and insights.

## Workflow / Pipeline Execution
A Databricks Workflow is created to automate the execution of the data pipeline.

Pipeline Execution Steps:

1. Bronze Notebook – Raw Data Ingestion  
2. Silver Notebook – Data Cleaning and Transformation  
3. Gold Notebook – Data Aggregation and Analytics  

The workflow ensures the notebooks run sequentially and the entire pipeline executes automatically.

## Project Structure
