# sql-data-warehouse-project
Developed a modern SQL Server Data Warehouse using Medallion Architecture (Bronze, Silver, Gold). Implemented ETL pipelines to extract, clean, and transform ERP and CRM data. Designed Star Schema models and performed SQL-based analytics to uncover insights into customer behavior, product performance, and sales trends.



# 📊 Data Warehouse and Analytics Project

## 🚀 Overview

Welcome to the Data Warehouse and Analytics Project!

This project demonstrates the development of a modern data warehouse using SQL Server. It focuses on integrating data from multiple source systems, implementing ETL processes, and performing SQL-based analytics to generate meaningful business insights.

The project follows industry-standard data engineering practices and showcases skills in SQL development, data warehousing, ETL, data modeling, and data analytics.

---

## 🏗️ Data Architecture

The project follows the **Medallion Architecture**, consisting of three layers: Bronze, Silver, and Gold.

![Data Architecture](docs/data_architecture.png)

- **Bronze Layer:** Stores raw data directly from ERP and CRM source systems using CSV files.
- **Silver Layer:** Performs data cleaning, standardization, and transformation to ensure data quality and consistency.
- **Gold Layer:** Contains business-ready data organized into fact and dimension tables using Star Schema modeling for reporting and analytics.

---

## 📖 Project Objectives

The main objectives of this project are:

- Design and build a modern data warehouse using SQL Server.
- Extract and load data from ERP and CRM source systems.
- Clean, transform, and integrate data using ETL processes.
- Develop fact and dimension tables using Star Schema.
- Perform SQL-based analysis to identify business insights.
- Generate reports related to customer behavior, product performance, and sales trends.

---

## 🛠️ Tools & Technologies

| Tool / Technology | Purpose |
|---|---|
| SQL Server Express | Database management and data warehousing |
| SQL Server Management Studio (SSMS) | SQL development and database management |
| SQL | Data extraction, transformation, and analysis |
| Draw.io | Data architecture and modeling diagrams |
| Git & GitHub | Version control and project management |
| CSV Files | Source data from ERP and CRM systems |

---

## 🔄 ETL Process

The project implements an ETL workflow across three layers:

1. **Extract:** Import raw CSV datasets from ERP and CRM source systems.
2. **Transform:** Clean, standardize, and integrate data to resolve data quality issues.
3. **Load:** Store transformed data in structured tables for analytical reporting.

---

## 📈 Analytics & Reporting

SQL-based analysis is performed to generate insights into:

- **Customer Analysis:** Understand customer behavior and purchasing patterns.
- **Product Analysis:** Evaluate product performance and sales contribution.
- **Sales Analysis:** Identify sales trends and monitor business performance.

These analyses help transform raw data into meaningful information for business decision-making.

---

## 📂 Repository Structure

```text
data-warehouse-project/
│
├── datasets/                   # Raw ERP and CRM datasets
│
├── docs/                       # Project documentation and diagrams
│   ├── etl.drawio
│   ├── data_architecture.drawio
│   ├── data_catalog.md
│   ├── data_flow.drawio
│   ├── data_models.drawio
│   └── naming-conventions.md
│
├── scripts/                    # SQL scripts for ETL and transformations
│   ├── bronze/                 # Raw data ingestion
│   ├── silver/                 # Data cleaning and transformation
│   └── gold/                   # Analytical data models
│
├── tests/                      # Data quality and testing scripts
│
├── README.md                   # Project documentation
├── LICENSE                     # License information
└── .gitignore                  # Git ignored files
```

---

## 🎯 Key Skills Demonstrated

- SQL Development
- Data Cleaning & Transformation
- ETL Pipeline Development
- Data Warehousing
- Medallion Architecture
- Star Schema & Data Modeling
- Data Analysis & Reporting
- Database Management

---

## 📌 Project Requirements

- **Data Sources:** ERP and CRM datasets provided in CSV format.
- **Data Quality:** Identify and resolve data inconsistencies.
- **Data Integration:** Combine multiple source systems into a unified data warehouse.
- **Data Modeling:** Design analytical fact and dimension tables.
- **Scope:** Focus on the latest available dataset without historical data tracking.
- **Documentation:** Maintain clear documentation of the architecture and data models.

---

## 📄 License

This project is licensed under the MIT License. You are free to use, modify, and distribute this project with appropriate attribution.

---

## 👩‍💻 Author

**Nimmi**

Aspiring Data Analyst | SQL | Excel | Data Analytics

Thank you for visiting my repository! ⭐
