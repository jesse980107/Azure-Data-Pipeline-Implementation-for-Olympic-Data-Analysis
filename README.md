# Data Engineering Project with Azure Synapse and Data Factory

## Overview

This project demonstrates a data pipeline using Azure Data Factory, Data Lake Gen 2, Azure Databricks, and Azure Synapse Analytics to process and analyze data from various sources. The processed data is then visualized using Power BI, Looker Studio, and Tableau.

## Architecture Diagram

![Architecture Diagram](Architecture%20Diagram.png)

The architecture consists of the following components:
1. **Data Source**: The origin of raw data.
2. **Data Integration**:
   - **Azure Data Factory**: Orchestrates data movement and transformation.
   - **Data Lake Gen 2**: Stores raw data.
3. **Transformation**:
   - **Azure Databricks**: Processes and transforms data.
   - **Data Lake Gen 2**: Stores transformed data.
4. **Analytics**:
   - **Azure Synapse Analytics**: Provides data integration and big data analytics.
5. **Dashboard**:
   - **Power BI, Looker Studio, Tableau**: Tools for data visualization.

## Data Pipeline

![Data Factory Pipeline](Data%20Factory%20Pipeline.png)

The pipeline in Azure Data Factory extracts, transforms, and loads data from different sources into Azure Data Lake Gen 2 for raw storage, then transforms it using Azure Databricks before storing the processed data back into Data Lake Gen 2.

## Data Transformation

The data transformation process in Azure Databricks involves using Spark to clean and process the data.

## SQL Analytics

![Azure Synapse Analytics](Azure%20Synapse%20Analtics.png)

Using Azure Synapse Analytics, we perform SQL queries to analyze the processed data stored in the data lake.

## Notebooks

Refer to the provided Jupyter Notebook for detailed steps on data transformation using Spark.

- [Data Transformation Notebook](Data%20Transformation%28Spark%29.ipynb)

## Visualization