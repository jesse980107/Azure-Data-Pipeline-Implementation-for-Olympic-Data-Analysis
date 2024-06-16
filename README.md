# End-To-End Data Engineering Project with Azure 

## Overview

This project demonstrates a comprehensive data pipeline using Azure Data Factory, Data Lake Gen 2, Azure Databricks, and Azure Synapse Analytics. The goal is to process and analyze data from the 2021 Tokyo Olympics and visualize the results using Power BI.

## Data Source

The original data for this project is sourced from the [2021 Olympics in Tokyo dataset on Kaggle](https://www.kaggle.com/datasets/arjunprasadsarkhel/2021-olympics-in-tokyo).

## Architecture Diagram

![Architecture Diagram](Architecture%20Diagram.png)

The architecture consists of the following components:
1. **Data Source**: Raw data origin.
2. **Data Integration**:
   - **Azure Data Factory**: Orchestrates data ingestion and initial transformation.
   - **Data Lake Gen 2**: Stores raw data in the `raw-data` folder.
3. **Transformation**:
   - **Azure Databricks**: Transforms and processes data using Apache Spark.
   - **Data Lake Gen 2**: Stores transformed data in the `transform-data` folder.
4. **Analytics**:
   - **Azure Synapse Analytics**: Performs advanced analytics and find insight.
5. **Dashboard**:
   - **Power BI, Looker Studio, Tableau**: Visualizes the processed data.

## Data Pipeline

![Data Factory Pipeline](Data%20Factory%20Pipeline.png)

### Steps:
1. **Ingestion**: Data is ingested from various sources using Azure Data Factory.
2. **Raw Storage**: Raw data is stored in the `raw-data` folder in Azure Data Lake Gen 2.
3. **Transformation**: Data is processed and transformed in Azure Databricks.
4. **Storage**: Transformed data is stored in the `transform-data` folder in Azure Data Lake Gen 2.
5. **Analytics**: Data is analyzed using Azure Synapse Analytics.
6. **Visualization**: Results are visualized using Power BI, Looker Studio, and Tableau.

## Data Transformation

Refer to the [Data Transformation Notebook](Data%20Transformation%28Spark%29.ipynb) for detailed steps on data cleaning and transformation using Spark in Azure Databricks.

## SQL Analytics

![Azure Synapse Analytics](Azure%20Synapse%20Analtics.png)

Using Azure Synapse Analytics, perform SQL queries to analyze the transformed data stored in Data Lake Gen 2.

## Visualization

Visualize the processed data using:
- **Power BI**: Create interactive dashboards and reports.
- **Looker Studio**: Generate detailed data visualizations.
- **Tableau**: Build comprehensive visual analytics.


