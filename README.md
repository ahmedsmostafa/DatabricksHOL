# Intro To Azure Databricks Hands On Lab

Azure Databricks is a new offering within the Microsoft Azure Data & Analytics space that provides a unified data engineering and data science platform.

Further information can be found [here](https://azure.microsoft.com/en-gb/resources/videos/azure-databricks-overview/).

This Hands On Lab (HOL) serves as a taster session for those getting started with Azure Databricks, and pulls together tutorials from existing documents such as those found in the [Azure docs](https://docs.microsoft.com/en-us/azure/azure-databricks/databricks-extract-load-sql-data-warehouse).

This is a starter level for those getting into Databricks, however it assumes some knowledge of creating resources in the Azure portal.

Specifically, we'll cover:

- Creating of resources in the Azure portal - Blob Storage, Azure SQL Data Warehouse, Service Principals, Azure Data Lake Storage (Gen 1 at time of writing) and of course, Azure Databricks.
- Building an ETL process with Azure Databricks that ingests a sample JSON file from Azure Data Lake, processes it within a Databricks Notebook and writes the processed file into Azure SQL Data Warehouse
- Getting Started with R Dataframes in Databricks using SparkR
- Building Logistic and Linear Regression Models with Azure Databricks and glm()

## Labs

This HOL can be used in two ways. You can either use the word documents as a guide and follow the intructions within, or follow the solution notebooks themselves and run the cells as required.

Regardless of which route you take, start here - [Lab 1 - Getting Started](https://github.com/midomsft/DatabricksHOL/blob/master/Labs/LAB01%20-%20Setting%20up%20Resources.docx)

- [Lab 01 - Setup](/Labs/LAB01%20-%20Setting%20up%20Resources.docx)
- [Lab 02 - Extract, Transformation and Loading With Azure Databricks](/labs/LAB02%20-%20Extract%2C%20transform%2C%20and%20load%20data%20using%20Azure%20Databricks.docx)
- [Lab 03 - Data Science With Azure Databricks](/Labs/LAB03%20-%20Data%20Science%20using%20Azure%20Databricks.docx)

## Solutions

The notebooks completed during the HOL can be found [here](https://github.com/midomsft/DatabricksHOL/tree/master/Solution%20Notebooks). When completed the Databrick steps in the HOL, you can either follow the step by step guide in the docs under Labs, or simply run through the notebooks directly to avoid switching between screens.

Within Databricks you can go to Workspace -> (Drop Down) -> Import -> Import Solution Notebooks (dbc files) into your own workspace.

## Data

This folder contains the small_radio_json.json file used in the ETL Lab.






