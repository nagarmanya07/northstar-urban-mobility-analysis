# NorthStar Urban Mobility and Logistics Database Analysis

This repository contains the database implementation and analysis for the NorthStar Urban Mobility and Logistics case study.

## Project Overview

The project demonstrates the use of both NoSQL and relational database approaches as part of a unified analytical solution. MongoDB Atlas was used for NoSQL database design and operational analysis, while SQLite within R was used for SQL-based relational querying.

## Technologies Used

- MongoDB Atlas
- Python
- PyMongo
- Google Colab
- R
- SQLite
- DBI
- RSQLite

## Repository Structure

- `python_processing/`  
  Contains the Python notebook used for MongoDB Atlas connection, data insertion, CRUD operations, indexing, aggregation and operational analysis.

- `r_analytics/`  
  Contains the R notebook used for SQLite database creation and SQL queries.

- `mongodb/`  
  Contains MongoDB-related supporting files or screenshots.

- `report_assets/`  
  Contains screenshots and report-related assets.

## Main Notebooks

- `python_processing/northstar_python_processing.ipynb`
- `r_analytics/r_analytics/northstar_sql_r_analysis.ipynb`

## Key Database Operations

### MongoDB and Python

- MongoDB Atlas connection using PyMongo
- Collection creation and document insertion
- CRUD operations
- Index creation
- Aggregation queries
- Sorting and filtering
- Operational analytical queries

### SQL and R

- SQLite database creation
- CSV import into SQL tables
- SELECT queries
- WHERE filtering
- ORDER BY sorting
- COUNT and AVG functions
- GROUP BY aggregation
- JOIN queries

## Key Findings

- Delayed and failed deliveries were identified as major operational issues.
- Some hubs showed weaker delivery performance.
- Delay-related complaints were common.
- Manual route override activity suggested potential route planning inefficiencies.
- App performance issues such as high API latency may affect customer experience.

## Author

Manya Nagar
