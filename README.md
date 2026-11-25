# E-Commerce Sales Data Engineering Pipeline

## Project Overview

The **E-Commerce Sales Data Engineering Pipeline** is an end-to-end data engineering project developed using **PySpark and Databricks** to process, transform, validate, and organize e-commerce sales data.

The project implements the ETL (Extract, Transform, Load) process using the **Medallion Architecture**, transforming raw data into structured, clean, and analytics-ready datasets.

An interactive five-page dashboard was also developed using Databricks AI/BI Dashboards to analyze sales performance, product trends, payment methods, and order lifecycle activities.

## Project Objectives

- Build an end-to-end ETL pipeline using PySpark.
- Extract and process raw e-commerce sales data.
- Clean and transform data to improve data quality.
- Implement Bronze, Silver, and Gold layers using Medallion Architecture.
- Perform data validation and quality checks.
- Prepare structured datasets for analytics and reporting.
- Develop an interactive dashboard to visualize business insights.

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| PySpark | Distributed data processing |
| Apache Spark | Big data processing engine |
| Databricks | Data engineering and pipeline execution |
| Databricks AI/BI Dashboards | Data visualization and reporting |

## ETL Pipeline Architecture

The project follows the **Medallion Architecture**, consisting of three processing layers.

### 1. Bronze Layer – Raw Data

- Extracts the original e-commerce sales data.
- Loads raw data into the Bronze layer.
- Maintains the initial structure of the source data.

### 2. Silver Layer – Cleaned Data

- Handles missing and inconsistent values.
- Performs data cleaning and transformation.
- Applies data quality checks.
- Prepares reliable and structured datasets.

### 3. Gold Layer – Business-Ready Data

- Organizes transformed data for analytical purposes.
- Creates business-level datasets and aggregations.
- Prepares data for dashboard development and reporting.

## Pipeline Workflow

```text
       Raw E-Commerce Sales Data
                  |
                  v
           Data Extraction
                  |
                  v
             BRONZE LAYER
               Raw Data
                  |
                  v
             SILVER LAYER
       Data Cleaning & Transformation
                  |
                  v
              GOLD LAYER
        Business-Ready Data
                  |
                  v
        Databricks AI/BI Dashboard
                  |
                  v
          Business Insights
```

## Dashboard

An interactive five-page dashboard was developed using **Databricks AI/BI Dashboards** to analyze e-commerce sales performance and generate meaningful business insights.

### Dashboard Pages

**1. Executive Overview**

Provides a high-level summary of overall business performance through key performance indicators and visual insights.

**2. Sales Analysis**

Analyzes sales performance, revenue trends, and sales-related patterns.

**3. Product Analysis**

Explores product-level performance and sales distribution to understand product trends.

**4. Payment Analysis**

Examines payment methods and transaction patterns to understand customer payment preferences.

**5. Order Lifecycle**

Tracks order-related activities and provides insights into the order lifecycle.

### Published Dashboard

[View E-Commerce Sales Dashboard](https://dbc-c555ecc8-77eb.cloud.databricks.com/dashboardsv3/01f1e7fc83f9151290a1f433ab1265a8/published/pages/order_lifecycle?o=7474658799844077)

## Dashboard Screenshots

### 1. Executive Overview
![Executive Overview](Screenshots/Executive%20Overview.jpg)

### 2. Sales Analysis
![Sales Analysis](Screenshots/Sales%20Analysis.jpg)

### 3. Product Analysis
![Product Analysis](Screenshots/Product%20Analysis.jpg)

### 4. Payment Analysis
![Payment Analysis](Screenshots/Payment%20Analysis.jpg)

### 5. Order Lifecycle
![Order Lifecycle](Screenshots/Order%20Lifecycle.jpg)

## Key Features

- End-to-end ETL pipeline implementation.
- Distributed data processing using PySpark.
- Medallion Architecture implementation.
- Data cleaning and transformation.
- Data quality validation.
- Analytics-ready Gold-layer datasets.
- Five-page interactive dashboard.
- Business insights through data visualization.

## Project Structure

```text
E-Commerce-Sales-Data-Engineering-Pipeline/
│
├── src/
│   ├── bronze/
│   ├── silver/
│   └── gold/
│
├── screenshots/
│   ├── Executive_Overview.png
│   ├── Sales_Analysis.png
│   ├── Product_Analysis.png
│   ├── Payment_Analysis.png
│   └── Order_Lifecycle.png
│
├── architecture/
└── README.md
```

## Key Learnings

- Understanding end-to-end data engineering workflows.
- Working with PySpark and Databricks.
- Implementing Medallion Architecture.
- Building ETL pipelines.
- Performing data cleaning and validation.
- Transforming raw data into business-ready datasets.
- Developing interactive dashboards using Databricks AI/BI Dashboards.
- Connecting data engineering outputs with business reporting.

## Acknowledgements

I would like to express my sincere gratitude to **Innomatics Research Labs** and my mentors for their guidance, support, and learning opportunities throughout this project.

This project helped me strengthen my practical understanding of data engineering concepts and gain hands-on experience with PySpark, Apache Spark, and Databricks.

---

**Project:** E-Commerce Sales Data Engineering Pipeline

**Domain:** Data Engineering

**Technologies:** Python | PySpark | Apache Spark | Databricks | AI/BI Dashboards
