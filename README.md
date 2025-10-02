# 📊 Data Warehouse and Analytics Project  

Welcome to the **Data Warehouse and Analytics Project** repository! 🚀  
This project demonstrates a comprehensive **data warehousing and analytics solution** — from building a data warehouse to generating actionable insights.  

Designed as a **portfolio project**, it highlights **industry best practices** in data engineering and analytics.  

---

## 🏗️ Data Architecture  

The project follows the **Medallion Architecture** (Bronze, Silver, Gold layers):  

1. **Bronze Layer:** Stores raw data as-is from the source systems. Data is ingested from **CSV files** into **SQL Server**.  
2. **Silver Layer:** Performs data **cleansing, standardization, and normalization** to prepare data for analysis.  
3. **Gold Layer:** Houses **business-ready data** modeled into a **star schema** for reporting and analytics.  

---

## 📋 Project Overview  

This project involves:  

1. **Data Architecture** – Designing a modern data warehouse using the Medallion approach.  
2. **ETL Pipelines** – Extracting, transforming, and loading data from ERP and CRM systems into the warehouse.  
3. **Data Modeling** – Developing fact and dimension tables optimized for analytical queries.  
4. **Analytics & Reporting** – Creating SQL-based reports and dashboards to deliver actionable insights.  

🎯 This repository is an excellent resource for:  
- SQL Development  
- Data Architecture  
- Data Engineering  
- ETL Pipeline Development  
- Data Modeling  
- Data Analytics  

---

## 🚀 Project Requirements  

### 🏗️ Building the Data Warehouse (Data Engineering)  

**Objective:**  
Develop a modern **Data Warehouse** using **SQL Server** to consolidate sales data, ensuring a **single source of truth** that supports **analytical reporting** and enables **informed business decision-making**.  

---

## 📌 Project Specifications  

- **Data Sources:** Import data from two systems (**ERP** and **CRM**) provided as CSV files.  
- **Data Quality:** Cleanse and resolve data quality issues before analysis.  
- **Integration:** Combine ERP and CRM data into a single, user-friendly data model optimized for queries.  
- **Scope:** Focus only on the latest dataset (no historization required).  
- **Documentation:** Provide clear documentation of the data model to support both business stakeholders and analytics teams.  

---

## 📊 BI: Analytics & Reporting  

### 🎯 Objective  
Develop **SQL-based analytics** to deliver insights into:  

- **Customer Behavior**  
- **Product Performance**  
- **Sales Trends**  

These insights empower stakeholders with **key business metrics**, enabling **data-driven strategic decision-making**.  

---

## 📂 Repository Structure  

| Folder / File | Description |
|---------------|-------------|
| `datasets/` | Raw datasets used for the project (ERP and CRM data) |
| `docs/` | Project documentation and architecture details |
| ├── `data_architecture.drawio` | Draw.io file showing the project's architecture |
| ├── `data_catalog.md` | Catalog of datasets, including field descriptions and metadata |
| ├── `data_flow.drawio` | Draw.io file for the data flow diagram |
| ├── `data_models.drawio` | Draw.io file for data models (star schema) |
| ├── `naming-conventions.md` | Consistent naming guidelines for tables, columns, and files |
| `scripts/` | SQL scripts for ETL and transformations |
| ├── `bronze/` | Scripts for extracting and loading raw data |
| ├── `silver/` | Scripts for cleaning and transforming data |
| ├── `gold/` | Scripts for creating analytical models |
| `tests/` | Test scripts and data quality checks |
| `README.md` | Project overview and instructions |

---

## 🛠️ Tools & Technologies  

- **SQL Server Express** – Lightweight database server for hosting the warehouse  
- **Draw.io** – Designing data architecture, models, and flows  
- **CSV Files** – Source data (ERP and CRM systems)  
- **SQL (ETL + Analytics)** – For transformations and reporting  

---

✨ This project demonstrates how raw ERP & CRM data can be transformed into a **robust data warehouse** that supports **business intelligence and analytics**.  
