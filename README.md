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

---

## 📺 YouTube Tutorial Reference

This project follows the concepts explained in the video:  
**"Data Warehouse | Data Modeling | Databricks | PySpark | SparkSQL"**

### 🕓 Timestamps:

- `0:00` Introduction  
- `07:15` What is Data Warehouse?  
- `12:42` Database vs Data Warehouse  
- `23:19` What is Data Warehousing  
- `28:29` ETL Layers  
- `34:04` Incremental Loading  
- `46:10` Databricks Free Account  
- `48:27` Databricks Overview  
- `57:32` Incremental Data Loading using Spark SQL  
- `1:19:02` What is Data Modeling  
- `1:25:45` What is Dimensional Data Modeling  
- `1:29:06` Fact Table and Dimension Tables  
- `1:37:37` Star Schema vs Snowflake Schema  
- `1:46:23` Dimension Tables and Fact Table using Spark SQL  
- `2:30:39` Types of Fact Tables  
- `2:40:34` Types of Dimension Tables  
- `2:49:47` Slowly Changing Dimensions  
- `3:00:00` Implementing SCD Type 1 in Databricks with Spark SQL  

---

## 🧑‍💻 Author

**Anjan Kumar Depuru**  
[LinkedIn](https://www.linkedin.com/in/anjan-kumar-depuru/) | [anjandepuru@gmail.com](mailto:anjandepuru@gmail.com)

---

## 📂 Folder Contents

- `sales_datawarehouse_build.sql` — Full SQL script with table creation, view logic, and insertions
- `README.md` — Project description and reference guide

---

## 🔄 How to Run

1. Upload `sales_datawarehouse_build.sql` to a Databricks SQL Workspace or convert to a Notebook
2. Ensure a cluster is running (DBR 11+ recommended)
3. Execute blocks sequentially
4. Use `SELECT` statements to validate each stage

---

## ⭐️ Star this repo if you find it helpful!
