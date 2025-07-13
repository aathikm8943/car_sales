# Azure End‑to‑End Data Engineering Project 🚀

**End-to-end data engineering pipeline using Azure Data Factory, Databricks, Delta Lake, and more.**

---

## 📚 Overview

This project demonstrates a job-ready, real-time data engineering solution on Microsoft Azure. It follows a structured medallion architecture (Bronze → Silver → Gold) and integrates major tools like Azure Data Factory, Azure Databricks, Delta Lake, and Azure SQL Database.

The key outcomes of this project include:

- Incremental data ingestion from external APIs
- Data transformation and validation using PySpark
- ACID-compliant storage with Delta Lake
- Star schema modeling for analytical workloads
- Secure access using Service Principals

---

## ✅ Tech Stack

| Tool / Service                | Purpose                                   |
|------------------------------|-------------------------------------------|
| Azure Data Factory (ADF)     | Data ingestion & orchestration            |
| Azure Databricks + PySpark   | Data transformation                       |
| Delta Lake                   | Versioned & optimized storage layer       |
| Azure Data Lake Gen2         | Raw and curated data storage              |
| Azure SQL Database           | Final data warehouse                      |
| GitHub                       | Version control and collaboration         |

---

## ⚙️ Project Architecture

```text
External API Source
        ↓
Azure Data Factory (Incremental Load)
        ↓
Bronze Layer (Raw)
        ↓
Databricks PySpark (Cleaning & Dedupe)
        ↓
Silver Layer (Cleaned Data)
        ↓
Star Schema Modeling (Fact & Dimensions)
        ↓
Gold Layer → Azure SQL DB

---
```
## ✅ Tech Stack
```
✅ Incremental ingestion with Watermarking

✅ Delta Lake Time Travel & Schema Enforcement

✅ Star Schema modeling with Fact & Dimension tables

✅ SCD Type 2 (Slowly Changing Dimensions)

✅ Secure authentication via Service Principal

---

```
## Learning Outcomes
```
1. Design and implement medallion architecture

2. Build scalable pipelines using ADF

3. Work with Delta Lake features (VACUUM, Time Travel, etc.)

4. Use PySpark in Databricks to clean, transform, and model data

5. Load and query analytical data from Azure SQL Database