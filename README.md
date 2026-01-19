# AdventurerWorks_Data_Pipeline_Project
## Introduction
This project demonstrates a Bronze–Silver–Gold ETL data pipeline using Azure services. Data is ingested with Azure Data Factory, transformed using PySpark in Azure Databricks, and analyzed with Azure Synapse Analytics, with insights visualized in Power BI.
## Architecture
![Project Architecture](Architecture.png)

## Technologies used
1. Microsoft Azure
   - Azure Data Factory
   - Synapse Analyitcs
   - Azure blob Storage
2. Dashboard - Power BI
3. Pyspark
## Dataset used
The project uses a structured dataset consisting of entities such as athletes, events, and medals. The dataset includes columns like athlete details, event information, and country-wise medal counts, and is used to demonstrate the Bronze–Silver–Gold ETL pipeline from raw ingestion to analytics-ready data.
## Transforamtion and Scripting
1. [ETl Script](ETL_script.ipynb)
2. [Views](Visulization.sql)
