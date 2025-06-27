# **Data Warehouse and Analytics Project**

**Data Warehouse and Analytics Project** repository!

This project presents a complete data warehousing and analytics solution—from building a data warehouse to delivering actionable business insights. Designed as a portfolio project, it showcases best practices in modern **data engineering**, **ETL**, **data modeling**, and **analytics**.

---

## Data Architecture

This project follows the **Medallion Architecture** with **Bronze**, **Silver**, and **Gold** layers:

* **Bronze Layer**: Stores raw data ingested from source systems (CSV files) directly into a SQL Server database.
* **Silver Layer**: Performs data cleansing, normalization, and standardization to prepare the data for analysis.
* **Gold Layer**: Contains business-ready data modeled in a **star schema** for reporting and analytics.

---

## Project Overview

The project covers the following:

* **Data Architecture**: Designing a modern data warehouse using Medallion Architecture.
* **ETL Pipelines**: Extracting, transforming, and loading data from ERP and CRM systems into the warehouse.
* **Data Modeling**: Creating **dimension** and **fact** tables optimized for analytical workloads.
* **Analytics & Reporting**: Writing SQL-based reports and dashboards to uncover insights.

---

## Project Requirements

### Data Engineering: Build the Data Warehouse

**Objective**: Develop a modern data warehouse using SQL Server to consolidate sales data for better decision-making.

**Key Specs:**

* **Data Sources**: ERP and CRM systems (CSV files)
* **Data Quality**: Clean and standardize the data before loading
* **Integration**: Merge sources into one analytical model
* **Scope**: Focus on the most recent data (no historization)
* **Documentation**: Provide clear data model documentation for analysts and business users

---

### Analytics & Reporting

**Objective**: Develop SQL-based reports to analyze:

* Customer Behavior
* Product Performance
* Sales Trends

These reports help drive strategic decisions with real business metrics.

---

## Repository Structure

```
data-warehouse-project/
│
├── datasets/                          # Raw ERP & CRM data (CSV files)
├── docs/                              # Documentation & diagrams
│   ├── etl.drawio
│   ├── data_architecture.drawio
│   ├── data_catalog.md
│   ├── data_flow.drawio
│   ├── data_models.drawio
│   ├── naming-conventions.md
│
├── scripts/                           # SQL ETL scripts
│   ├── bronze/
│   ├── silver/
│   ├── gold/
│
├── tests/                             # Data quality and validation scripts
├── README.md                          # Project overview
├── LICENSE                            # MIT License
├── .gitignore                         # Git ignore rules
└── requirements.txt                   # Project dependencies
```

---

## License

This project is licensed under the **MIT License**. You're free to use, modify, and share it with proper credit.

---

## About Me

Hi, I'm **João Miguel** — an **aspiring data professional** passionate about transforming raw data into valuable insights.
This project is part of my journey to master modern data practices and share them with others.
Let’s learn and grow together!
