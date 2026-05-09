# DS2002
Final Project Repository

# AdventureWorks Data Lakehouse

## Overview
A dimensional data lakehouse built using PySpark and the Medallion Architecture (Bronze/Silver/Gold).

## Architecture
- **Batch Layer**: Data was extracted from MySQL and CSV/JSON files
- **Streaming Layer**: Spark AutoLoader processed the JSON files to simulate the real-time data component
- **Bronze**: Here was the raw ingested data
- **Silver**: Next, data was clean and joined with dimension tables (including date dimension)
- **Gold**: Aggregated analytics-ready tables were analyzed for business insights

## Data Sources
- MySQL: AdventureWorks OLTP database; batch read for customers, employees, and date dimensions 
- MongoDB: JSON source; batch read for products dimension
- Files: CSV/JSON batch files

## Dimensions
- dim_date, employees, products, customers

## Fact Tables
- fact_purchase_orders

<img width="570" height="427" alt="image" src="https://github.com/user-attachments/assets/278d40f3-91f0-48a3-804c-496ab63d0e1b" />
