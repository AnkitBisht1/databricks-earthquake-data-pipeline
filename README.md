# Earthquake Data Engineering Pipeline (Databricks)

## Project Overview
This project demonstrates a data engineering pipeline built using Databricks to process earthquake data. The pipeline follows the Medallion Architecture to transform raw seismic data into structured datasets for analytics and reporting. The goal is to automate data processing and provide reliable earthquake insights for analysis and decision-making.

## Technologies Used
- Databricks
- SQL
- ETL Pipelines
- Medallion Architecture
- Data Transformation
- Workflow Automation

## Architecture
The project follows the Medallion Architecture:

Bronze Layer  
- Ingests raw earthquake data from the source dataset.  
- Stores raw data without modification.

Silver Layer  
- Cleans and transforms the data.  
- Handles missing values and standardizes the dataset.

Gold Layer  
- Aggregates and prepares curated datasets.  
- Used for analytics, reporting, and insights.

## Workflow / Pipeline Execution
A Databricks workflow is created to automate the pipeline execution.

Pipeline Steps:
1. Bronze Layer Notebook – Raw Data Ingestion  
2. Silver Layer Notebook – Data Cleaning and Transformation  
3. Gold Layer Notebook – Data Aggregation and Analytics  

The workflow ensures that notebooks run sequentially and the pipeline executes automatically.

## Project Structure
