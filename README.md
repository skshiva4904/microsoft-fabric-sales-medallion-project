# Microsoft Fabric Sales Medallion Architecture Project

## Project Overview
This project demonstrates an end-to-end data analytics pipeline built using Microsoft Fabric. The project follows the Medallion Architecture (Bronze, Silver, Gold) to process and transform sales data for analytics.

## Architecture
Data Source → Bronze Layer → Silver Layer → Gold Layer → Semantic Model → Power BI Dashboard

## Technologies Used
Microsoft Fabric
Dataflow Gen2
Lakehouse
SQL Endpoint
Power BI
DAX

## Project Workflow

Bronze Layer
Raw sales data is ingested into the Lakehouse using Dataflow.

Silver Layer
Data cleaning and transformation are performed to standardize the dataset.

Gold Layer
Business-ready aggregated tables are created for reporting.

Pipeline
A Fabric pipeline orchestrates the dataflow execution.

Semantic Model
The semantic model defines relationships and measures for analytics.

Dashboard
Power BI dashboard visualizes KPIs such as revenue, product performance, and sales trends.

## Author
Shivratna Kedar