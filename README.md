# 📊 SQL Data Warehouse Project

This project demonstrates an **end-to-end data warehouse and analytics solution** built using **SQL Server** and modern **data engineering best practices**.

The goal of this project is to transform raw ERP and CRM data into a **business-ready analytical model** that supports reporting and decision-making.

---

## 🏗️ Data Architecture

### 📐 Architecture Diagram
![Data Architecture](docs/data_architecture.png)


The project follows the **Medallion Architecture**:

### 🟤 Bronze Layer
- Raw data ingestion from CSV files
- Data stored as-is from ERP and CRM systems

### ⚪ Silver Layer
- Data cleansing and transformation
- Standardization and normalization
- Data quality handling

### 🟡 Gold Layer
- Business-ready data
- Star schema (Fact & Dimension tables)
- Optimized for analytics and reporting

---

## 📌 Project Objectives

- Build a modern **SQL-based data warehouse**
- Integrate multiple source systems
- Apply **ETL pipelines**
- Create analytical data models
- Generate insights using SQL queries

---

## 🛠️ Tools & Technologies

- SQL Server Express
- SQL Server Management Studio (SSMS)
- CSV datasets (ERP & CRM)
- Draw.io (Architecture & Data Models)
- Git & GitHub

---

## 📂 Repository Structure


sql-data-warehouse-project/
│
├── datasets/
│ └── raw ERP and CRM CSV files
│
├── docs/
│ ├── etl.drawio # ETL techniques and workflows
│ ├── data_architecture.drawio # Overall architecture
│ ├── data_flow.drawio # Data flow diagram
│ ├── data_models.drawio # Star schema models
│ ├── data_catalog.md # Dataset descriptions & metadata
│ └── naming-conventions.md # Naming standards
│
├── scripts/
│ ├── bronze/ # Raw data ingestion scripts
│ ├── silver/ # Data cleaning & transformation
│ └── gold/ # Analytical models
│
├── tests/ # Data quality checks
│
├── README.md
├── LICENSE
├── .gitignore
└── requirements.txt


---

## 📊 Analytics & Insights

SQL-based analytics are created to analyze:

- Customer behavior
- Product performance
- Sales trends

These insights enable stakeholders to make **data-driven decisions**.

---

## 🧠 Skills Demonstrated

- SQL Development
- Data Warehousing
- ETL Pipeline Design
- Data Modeling (Star Schema)
- Data Analysis & Reporting


---


## 👤 About Me

Hi, I’m **Rupan raj** 👋  
An aspiring **Data Engineer / Data Analyst** with hands-on experience in SQL, data warehousing, and analytics projects.

🔗 GitHub: https://github.com/RahulRupan



