# Retail Data Engineering Pipeline

A complete data engineering solution for retail analytics built on Databricks Lakehouse platform.

## Project Overview
This project implements a medallion architecture (Bronze → Silver → Gold) for retail data processing and analytics.

## Notebooks

1. **01_blob_to_bronze.ipynb** - Data ingestion from blob storage to Bronze layer using Auto Loader
2. **02_Gold_View.ipynb** - Gold layer transformations and aggregations
3. **03_calendar.ipynb** - Calendar dimension table creation for time-based analytics
4. **04_Metric View.ipynb** - Business metrics and KPIs calculation

## Architecture
- **Bronze Layer**: Raw data ingestion from source systems
- **Silver Layer**: Cleaned and validated data
- **Gold Layer**: Business-level aggregations and metrics

## Technologies
- Databricks
- Apache Spark
- Delta Lake
- Auto Loader

## Author
Built with Databricks Lakehouse Platform
