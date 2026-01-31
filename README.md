# 📊 Data Warehouse and Analytics Project

Welcome to the Data Warehouse and Analytics Project repository! 🚀  
This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a portfolio project, it highlights industry best practices in data engineering and analytics.

---

## 🏗️ Data Architecture

The data architecture for this project follows the **Medallion Architecture** using **Bronze, Silver, and Gold layers**.

### 🟤 Bronze Layer
- Stores raw data as-is from the source systems  
- Data is ingested from **CSV files** into a **SQL Server database**

### ⚪ Silver Layer
- Performs data cleansing, standardization, and normalization  
- Resolves data quality issues to prepare data for analysis

### 🟡 Gold Layer
- Houses business-ready data  
- Data is modeled into a **Star Schema** for reporting and analytics

---

### 📐 Architecture Diagram
![Data Architecture](image.png)



---

## 📖 Project Overview

This project involves:

- **Data Architecture**: Designing a modern data warehouse using the Medallion Architecture  
- **ETL Pipelines**: Extracting, transforming, and loading data from source systems  
- **Data Modeling**: Developing fact and dimension tables optimized for analytical queries  
- **Analytics & Reporting**: Creating SQL-based reports and dashboards for actionable insights  

---

## 🎯 Skills Demonstrated

This repository is an excellent resource for showcasing expertise in:

- SQL Development  
- Data Architecture  
- Data Engineering  
- ETL Pipeline Development  
- Data Modeling  
- Data Analytics  

---

## 🛠️ Tools & Technologies

All tools used in this project are **free**:

- Datasets (CSV files)
- SQL Server Express
- SQL Server Management Studio (SSMS)
- Git & GitHub
- Draw.io
- Notion

---

## 🚀 Project Requirements

### Building the Data Warehouse (Data Engineering)

**Objective**  
Develop a modern data warehouse using SQL Server to consolidate sales data and enable analytical reporting.

**Specifications**
- Data Sources: ERP and CRM systems (CSV files)
- Data Quality: Clean and resolve data issues prior to analysis
- Integration: Combine multiple sources into a unified analytical model
- Scope: Latest dataset only (no historization)
- Documentation: Clear data model documentation for stakeholders

---

### BI: Analytics & Reporting (Data Analysis)

**Objective**  
Develop SQL-based analytics to deliver insights into:

- Customer Behavior  
- Product Performance  
- Sales Trends  

These insights empower stakeholders with key business metrics.

For more details, refer to `docs/requirements.md`.

---

## 📂 Repository Structure


data-warehouse-project/
│

├── datasets/                           # Raw datasets used for the project (ERP and CRM data)

│

├── docs/                               # Project documentation and architecture details

│   ├── etl.drawio                      # Draw.io file shows all different techniquies and methods of ETL

│   ├── data_architecture.drawio        # Draw.io file shows the project's architecture

│   ├── data_catalog.md                 # Catalog of datasets, including field descriptions and metadata

│   ├── data_flow.drawio                # Draw.io file for the data flow diagram

│   ├── data_models.drawio              # Draw.io file for data models (star schema)

│   ├── naming-conventions.md           # Consistent naming guidelines for tables, columns, and files

│

├── scripts/                            # SQL scripts for ETL and transformations

│   ├── bronze/                         # Scripts for extracting and loading raw data

│   ├── silver/                         # Scripts for cleaning and transforming data

│   ├── gold/                           # Scripts for creating analytical models

│

├── tests/                              # Test scripts and quality files

│

├── README.md                           # Project overview and instructions

├── LICENSE                             # License information for the repository

├── .gitignore                          # Files and directories to be ignored by Git

└── requirements.txt                    # Dependencies and requirements for the project





