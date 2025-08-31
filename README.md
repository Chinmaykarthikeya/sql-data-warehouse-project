# Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project** repository! 🚀  
This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a portfolio project, it highlights industry best practices in data engineering and analytics [10].

---

## 🏗️ Data Architecture

This project follows the **Medallion Architecture** pattern:

- **Bronze Layer:** Stores raw data as-is from source systems, ingested from CSV files into SQL Server [10].
- **Silver Layer:** Includes data cleansing, standardization, and normalization, preparing data for analysis [10].
- **Gold Layer:** Houses business-ready data modeled into a **star schema** for reporting and analytics [10].

---

## 📖 Project Overview

Main components of the project [10]:

- **Data Architecture:** Modern design using Medallion Architecture layers.
- **ETL Pipelines:** Extract, transform, and load data from source systems.
- **Data Modeling:** Fact and dimension tables for optimal analytical queries.
- **Analytics & Reporting:** SQL-based reports and dashboards for actionable insights.

This repository is ideal for developing expertise in:

- **SQL Development**
- **Data Architecture**
- **Data Engineering**
- **ETL Pipeline Development**
- **Data Modeling**
- **Data Analytics**

---

## 🛠️ Important Links & Tools

All tools and materials are free [10]:

- **Datasets:** Project data (ERP and CRM, CSV format).
- **SQL Server Express:** Lightweight SQL database server.
- **SQL Server Management Studio (SSMS):** Database GUI.
- **Git & GitHub:** Version control and collaboration.
- **DrawIO:** Diagrams for data architecture, flows, and models.
- **Notion Template:** Project management and phases.

Direct resource links:
- [Datasets](datasets/)
- [SQL Server Express](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)
- [SSMS](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16)
- [DrawIO](https://www.drawio.com/)
- [Notion Project Template](https://www.notion.com/templates/sql-data-warehouse-project)
- [Project Steps (Notion)](https://thankful-pangolin-2ca.notion.site/SQL-Data-Warehouse-Project-16ed041640ef80489667cfe2f380b269?pvs=4)

---

## 🚀 Project Requirements

### Building the Data Warehouse (Data Engineering)

**Objective:**  
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making [10][1].

**Specifications:**
- **Data Sources:** Import from ERP and CRM systems, provided as CSV files.
- **Data Quality:** Cleanse and resolve quality issues before analysis.
- **Integration:** Combine both sources into a user-friendly analytical model.
- **Scope:** Use the latest dataset; historization is not required.
- **Documentation:** Document the data model for stakeholders & analytics teams.

---

### BI: Analytics & Reporting (Data Analysis)

**Objective:**  
Develop SQL-based analytics for detailed insights into:

- **Customer Behavior**
- **Product Performance**
- **Sales Trends**

These insights provide key business metrics for strategic decision-making [10][1].

See [`docs/requirements.md`](docs/requirements.md) for detailed analytics specifications.

---


---


---

## 🛡️ License

Licensed under the **MIT License**.  
You are free to use, modify, and share this project with proper attribution [10].

---

## 🌟 About
Building a modern data warehouse with SQL Server, covering ETL, data modeling, and advanced analytics.

---

## Topics

- data-science
- sql
- sql-server
- etl
- data-warehouse
- sql-query
- datascience
- data-engineering
- data-analytics
- datawarehousing
- data-analysis
- sqlserver
- datawarehouse
- data-cleaning
- datalake
- data-warehousing
- etl-pipeline
- etl-job
- data-lakehouse
- medallion-architecture





## 📂 Repository Structure

data-warehouse-project/
│
├── datasets/                       # Raw datasets (ERP and CRM data)
│
├── docs/                           # Project documentation and architecture details
│   ├── etl.drawio                  # ETL methods and diagrams
│   ├── data_architecture.drawio    # Project architecture diagrams
│   ├── data_catalog.md             # Dataset catalog and field metadata
│   ├── data_flow.drawio            # Data flow diagrams
│   ├── data_models.drawio          # Data models (star schema)
│   ├── naming-conventions.md       # Naming guidelines for tables and columns
│
├── scripts/                        # SQL scripts for ETL and transformations
│   ├── bronze/                     # Raw extraction and load scripts
│   ├── silver/                     # Data cleaning and transformation scripts
│   ├── gold/                       # Analytical model creation scripts
│
├── tests/                          # Test scripts and data quality checks
│
├── README.md                       # Project overview and instructions
├── LICENSE                         # License information
├── .gitignore                      # Files/directories to exclude from Git
└── requirements.txt                # Project dependencies

