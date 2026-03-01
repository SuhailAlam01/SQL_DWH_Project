# SQL_DWH_Project

## 📊 Modern Data Warehouse using SQL Server (Medallion Architecture)

This project demonstrates the implementation of a **Modern Data Warehouse** using **Microsoft SQL Server**, following the **Medallion Architecture** approach with **Bronze, Silver, and Gold layers**.

The project covers end-to-end data warehousing concepts including **ETL pipelines**, **data transformation**, **dimensional modeling**, and **analytics-ready datasets**.

---

## 🚀 Project Overview

The objective of this project is to design a scalable and structured Data Warehouse that converts raw data into high-quality analytical data for reporting and business intelligence.

Key components:

- Data ingestion from source systems
- Multi-layer data transformation
- Data quality improvement
- Dimensional modeling
- Analytical querying

---

## 🏗️ Architecture — Medallion Design

The warehouse follows a **three-layer Medallion Architecture**:

### 🥉 Bronze Layer — Raw Data
- Stores raw data exactly as received from source systems
- Minimal transformation
- Historical data preserved
- Used for auditing and traceability

**Purpose:**
- Data ingestion
- Source backup
- Replay capability

---

### 🥈 Silver Layer — Cleaned & Transformed Data
- Data cleaning and validation
- Standardized formats
- Removed duplicates
- Business rules applied

**Transformations include:**
- Handling NULL values
- Data type corrections
- Data normalization
- Data quality checks

---

### 🥇 Gold Layer — Business & Analytics Layer
- Analytics-ready datasets
- Aggregated and modeled data
- Star schema implementation

**Contains:**
- Fact tables
- Dimension tables
- KPI-ready datasets

Used directly for:
- Reporting
- Dashboards
- Business analysis

---

## ⚙️ Technologies Used

- Microsoft SQL Server
- T-SQL
- SQL Server Management Studio (SSMS)
- ETL Processes
- Dimensional Modeling (Star Schema)

---

## 🔄 ETL Workflow

### Extract
- Load raw data into Bronze layer

### Transform
- Clean and standardize data in Silver layer

### Load
- Build dimensional models in Gold layer

---

## 🧱 Data Modeling

Gold layer follows **Dimensional Modeling**:

- **Fact Tables** → Business metrics
- **Dimension Tables** → Descriptive attributes

Example Tables:
- Fact_Sales
- Dim_Customer
- Dim_Product
- Dim_Date

---

## 📈 Analytics Capabilities

The warehouse enables:

- Sales trend analysis
- Customer behavior insights
- Performance KPIs
- Aggregated reporting queries

---

## 📂 Project Structure

```
SQL_DWH_Project/
│
├── bronze/        # Raw ingestion scripts
├── silver/        # Data cleaning & transformations
├── gold/          # Data models & analytics tables
├── etl/           # ETL pipeline scripts
├── datasets/      # Source data
└── README.md
```

---


## 🎯 Learning Outcomes

- Modern Data Warehouse architecture
- Medallion data design pattern
- SQL-based ETL development
- Data modeling best practices
- Analytical SQL querying

---

## 🔮 Future Improvements

- Power BI integration
- Automated ETL scheduling
- Incremental loading strategy
- Data quality monitoring

---

## 👤 Author

**Suhail Alam**

---

## 📄 License

This project is created for educational and portfolio purposes.
**Suhail Alam**

---

## 📄 License

This project is for educational and learning purposes.
