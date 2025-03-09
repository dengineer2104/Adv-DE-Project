# Project Overview

**Integrated the Github API seamlessly into Azure Data Factory through the Rest_Api service. Stored the JSON data in the ADLS Gen2, organized within the bronze folder.**

**Further, used Databricks which collects data from the bronze folder and performs some transformations like dropping a column, padding, etc. Data gets stored into the silver folder with parquet delta format.**

**In the final transformation phase, data from the silver folder is transformed to meet business needs. This includes minor changes like column renaming and essential operations such as grouping, calculations, enrichments, and use-case optimizations.**

**After data enters the gold layer, it's utilized in Azure Synapse Analytics for advanced analysis, including metrics like average sales per category, identifying categories with the highest and lowest profits, and many more…**

**Data Visualization with PowerBI to present into a comprehensible format.**

## Services Used
- **Azure Data Factory** for seamless workflow automation.
- **Azure Databricks** for transformation.
- **Azure Data Lake Gen 2** for secure data management.
- **Azure Synapse Analytics** for complex analytics.
- **Azure Storage Account** for reliable storage.
- **Azure Key Vault & Azure Active Directory** for security & governance.

## Dataset Used
This is an E-Commerce dummy API.

## Project Goals
- **Data Ingestion** — Build a mechanism to ingest data from API.
- **ETL System** — We are getting data in raw format, transforming this data into the proper format.
- **Data Lake** — We will be getting data from API so we need a location to store them.
- **Scalability** — As the size of our data increases, we need to make sure our system scales with it.
- **Cloud** — We can’t process API data, so we need to use the cloud. In this case, we will use Azure.
- **Reporting** — Build a dashboard to get answers to the questions we asked earlier.

## Architecture Diagram
![Architecture Diagram](https://github.com/dengineer2104/Adv-DE-Project/blob/main/architecture%20diagram.gif)

##WorkSnapShots
![1](https://github.com/dengineer2104/Adv-DE-Project/blob/main/image%20(1).png)
![2](https://github.com/dengineer2104/Adv-DE-Project/blob/main/image.png)
