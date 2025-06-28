# sql-data-warehouse-project
# DATA WAREHOUSE PROJECT

**FROM SCRATCH**

## PROJECT OVERVIEW

Este proyecto implementa un data warehouse en un entorno real de producción, siguiendo los procesos ETL/ELT para transformar datos sin procesar en información empresarial de negocios útil.

This project involves:

- Data Architecture: Designing a Moder Data Warehouse using Medallion Architecture (Bronze, Silver and Gold layers)
- ETL Pipelines: Extracting, transforming and loading data from source systems into the warehouse
- Data Modeling: Developing fact and dimension tables optimized for analytical queries
- Analytics & Reporting: Creating SQL-based reports and dashboards for actionable insights

---

## ARCHITECTURE

### Medallion Architecture

- **Bronze Layer:** Batch processing, full load, **No Transformation (raw files)**
- **Silver Layer:** Batch processing, full load, **Transformation (data cleaning, standarization, normalization etc)**
- **Gold Layer:** No load (views), **Transformation (integrations, aggregation, business logics etc)**

![architecture](https://github.com/user-attachments/assets/819b5beb-a61c-4a6a-a3ab-7a24ab2d35bc)

---
## Links & Tools used

- **Sources: CRM, ERP (csv files)**
- **SQL Server Express:** Server for hosting SQL database
- **SQL Server Management Studio (SSMS):** GUI for managing and interacting with databases
- **Notion:** Documentation & detailed project tasks and phases
- **Draw.io:** Design and diagramming data architecture, models, flows etc
- **GitHub:** Repository to manage version and document code efficiently

---

## Project Requirements

### Building the Data Warehouse (Data Engineering)

**Objective**

Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed desicion-making.

**Specifications**

- **Data Sources:** Import data from two sources systems (ERP and CRM) provided as CSV files
- **Data Quality:** Cleanse and resolve data quality issues prior to analysis
- **Integration:** Combine both sources into a single, user-friendly data model designed for analytical queries
- **Scope:** Focus on the latest dataset only; historization data is not required
- **Documentation:** Provide clear documentation of the data model to support both business stakeholders and analytics teams

---

### BI: Analytics & Reporting (Data Analysis)

**Objective**

Develop SQL-based analytics to deliver detailed insights into

- **Customer Behavior**
- **Product Performance**
- **Sales Trends**

These insights empower stakeholders with key business metrics, enabling strategic desicion-making

---

## **🛡️ License**

This project is licensed under the MIT License.

---

## **🌟 About me**

Hi! I’m Alberto Mtz, a SQL-focused programmer who believes data tells powerful stories. Through this project, I demostrate my ability to transform raw data into actionable insights, combining technical skills with a curiosity to uncover hidden narratives


