# Olympic-Data-Analysis
## Introduction
This project involves developing an ETL pipeline to analyze Olympic data. The pipeline extracts data from various sources, transforms it into a suitable format, and loads it into an Azure data store for further analysis.

## Architecture
![Architecture Diagram](https://raw.githubusercontent.com/Aravindsuresh5235/-Olympic-Data-Analysis-/main/Olympic%20Data%20analysis%20(Architecture).png)
## Dataset/API
The dataset includes detailed information about Olympic events, athletes, and results from various years.

## Azure Services Used
1-Storage (Azure Blob Storage) 

2-Compute (Azure Databricks)

3-Data Orchestration (Azure Data Factory)

4-Data Warehouse (Azure Synapse Analytics)

5-Analytics Query (Azure Synapse Analytics)

## Project Execution Flow
1-Extracting Data

   *Connect to data sources and fetch Olympic event data.
 
   *Deploy processing code on Azure Databricks.
 
2-Automating Extraction

   *Schedule and automate data extraction with Azure Data Factory.
 
3-Transforming Data

   *Use PySpark on Databricks for data transformations.
 
4-Storing Data

   *Store raw and processed data in Azure Blob Storage.
 
   *Implement lifecycle policies for cost optimization.

5-Analyzing Data

   *Catalog and analyze data using Azure Synapse Analytics.
 
   *Create and query analytics tables for insights.
