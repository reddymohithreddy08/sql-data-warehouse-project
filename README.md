# Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project** repository! 🚀  
This project demonstrates a comprehensive data warehousing and analytics solution — from building a data warehouse to generating actionable insights.  
Designed as a portfolio project, it highlights industry best practices in data engineering and analytics.

---

## 🏗️ Data Architecture

The project follows the **Medallion Architecture** with three key layers: **Bronze**, **Silver**, and **Gold**.


1. **Bronze Layer**: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.  
2. **Silver Layer**: Handles data cleansing, standardization, and normalization to prepare data for analysis.  
3. **Gold Layer**: Contains business-ready, curated data modeled into a star schema optimized for analytics and reporting.

---

## 📖 Project Overview

This project involves the following major components:

1. **Data Architecture** – Design a modern data warehouse using Medallion Architecture.  
2. **ETL Pipelines** – Extract, transform, and load data from multiple source systems.  
3. **Data Modeling** – Develop fact and dimension tables for efficient analytical querying.  
4. **Analytics & Reporting** – Generate actionable insights through SQL-based reports and dashboards.

🎯 This project showcases core skills for roles such as:
- SQL Developer  
- Data Engineer  
- Data Architect  
- ETL Pipeline Developer  
- Data Modeler  
- Data Analyst  

---

## 🛠️ Tools & Resources

Everything used in this project is **free and open-source**:

- **[Datasets](datasets/):** Access project data (ERP and CRM CSV files).  
- **[SQL Server Express](https://www.microsoft.com/en-us/sql-server/sql-server-downloads):** Lightweight SQL database server.  
- **[SQL Server Management Studio (SSMS)](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms):** GUI for database management and query execution.  
- **[GitHub](https://github.com/):** Version control and code collaboration platform.  
- **[Draw.io](https://www.drawio.com/):** For creating architecture diagrams, ER models, and data flows.  
- **[Notion](https://www.notion.com/):** Used for project planning and task management.  
- **[Notion Project Steps](https://thankful-pangolin-2ca.notion.site/SQL-Data-Warehouse-Project-16ed041640ef80489667cfe2f380b269?pvs=4):** Complete guide for all project phases and steps.

---

## 🚀 Project Requirements

### 🧱 Data Engineering (Building the Data Warehouse)

**Objective:**  
Design and build a modern data warehouse using SQL Server to consolidate and analyze sales data.

**Specifications:**
- **Data Sources:** Import data from two systems (ERP and CRM) using CSV files.  
- **Data Quality:** Cleanse and resolve inconsistencies before loading.  
- **Integration:** Combine both sources into a unified analytical data model.  
- **Scope:** Focus on current data only (no historical data).  
- **Documentation:** Clearly explain data models for business and analytics teams.

---

### 📊 Data Analysis & Reporting (BI)

**Objective:**  
Deliver SQL-based analytics to generate insights on:
- Customer behavior  
- Product performance  
- Sales trends  

These insights support data-driven decision-making and business strategy.  

For more details, see [docs/requirements.md](docs/requirements.md).

---

## 📂 Repository Structure

