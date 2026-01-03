# Databricks-assignment - Parcel Delivery Quality

## Overview

This repository contains Databricks notebooks located in the `tasks` folder. Each notebook addresses a specific step in the data pipeline for the "Parcel Delivery Quality" assignment.

## Notebooks in `tasks` Folder

- **Extract & Deduplicate Silver Data:** Notebooks for extracting and deduplicating data from Silver tables.
- **Transform & Classify:** Scripts for transforming and classifying the data using Spark.
- **Upsert Fact Table:** Notebooks for upserting records into the fact table.
- **Upsert Dimension Tables:** Notebooks for upserting records into dimension tables.
- **Update Watermark:** Scripts for updating the processing watermark.
- **Analysis & Visualization:** Exploratory data analysis and visualizations to understand delivery quality metrics.

## Usage in Databricks Jobs

Each notebook in the `tasks` folder is configured as a separate task within a Databricks Job. The job orchestrates the execution order, ensuring data flows seamlessly from extraction and deduplication to analysis.

## Power BI Report

The final task was to generate a Power BI report for the "Parcel Delivery Quality" assignment using Power BI Service. This report was built directly from the fact and dimension tables; no Databricks notebook was created for this step.

## Assignment Structure

1. Extract & Deduplicate Silver Data
2. Transform & Classify
3. Upsert Fact Table
4. Upsert Dimension Tables
5. Update Watermark
6. Generate Power BI report in Power BI Service - [PowerBI Report](https://app.powerbi.com/links/q6JeU7A2cY?ctid=e0fd2e2c-4d5f-4cd3-98dc-2d69895120d7&pbi_source=linkShare)

---