# 🧠 Sales Data Warehouse Project | Databricks + PySpark + SparkSQL

This project demonstrates the **end-to-end development of a Data Warehouse** solution on **Databricks**, using **PySpark**, **Spark SQL**, and best practices in **dimensional data modeling**.

It covers essential data warehousing concepts including:
- ETL pipeline creation
- Incremental data loading
- Star schema design
- Fact & dimension table creation
- Slowly Changing Dimensions (SCD Type 1) implementation

> ✅ Built and tested in **Databricks** using **SparkSQL** and **PySpark notebooks**.

---

## 📌 Key Concepts Covered

- Data Warehouse Architecture
- Database vs. Data Warehouse
- ETL Layers (Staging → Transformation → Core)
- Incremental Data Loading using Spark SQL
- Dimensional Modeling (Fact & Dimension Tables)
- Star Schema vs. Snowflake Schema
- SCD Type 1 (Slowly Changing Dimensions)
- Databricks Lakehouse Concepts

---

## 🧱 Technologies Used

- **Databricks**
- **Apache Spark (PySpark + SparkSQL)**
- **Delta Lake**
- **SQL & Views**
- **Dimensional Modeling (Star Schema)**

---

## 🗃️ Data Warehouse Structure

**Schemas:**
- `sales_scd`: Raw + SCD logic
- `orderDWH`: Modeled schema with dimensions and fact tables

**Layers:**
- `Staging Layer`: Raw data loaded from source
- `Transformation Layer`: Cleaned & enriched views
- `Core Layer`: Fact and Dimension tables

**Tables Created:**
- `DimCustomers`
- `DimProducts`
- `DimRegion`
- `DimDate`
- `FactSales`



