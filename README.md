# DS2002
Final Project Repository

# AdventureWorks Data Lakehouse

## Overview
A dimensional data lakehouse built using PySpark and the Medallion Architecture (Bronze/Silver/Gold).

## Architecture
- **Batch Layer**: Data extracted from MySQL and CSV/JSON files
- **Streaming Layer**: Spark AutoLoader processes JSON files simulating real-time data
- **Bronze**: Raw ingested data
- **Silver**: Cleaned and joined with dimension tables
- **Gold**: Aggregated analytics-ready tables

## Data Sources
- MySQL: AdventureWorks OLTP database (
- MongoDB: 
- Files: CSV/JSON batch files

## Dimensions
- dim_date, employees, products, customers

## Fact Tables
- fact_purchase_orders

<img width="570" height="427" alt="image" src="https://github.com/user-attachments/assets/278d40f3-91f0-48a3-804c-496ab63d0e1b" />
