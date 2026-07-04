# 🏦 Banking Data Warehouse & ETL Project

An end-to-end **Banking Data Warehouse** project built using **SQL Server** and **SQL Server Integration Services (SSIS)** as part of my **Data Engineering learning journey**.

---

## 📌 Project Overview

This project demonstrates how to design and implement a complete ETL pipeline that extracts banking data from an OLTP database, transforms it, and loads it into a **Star Schema Data Warehouse** for reporting and analytics.

---

## 🚀 Features

- ⭐ Star Schema Design
- 🔄 ETL Pipeline using SSIS
- 📈 Slowly Changing Dimension (SCD Type 2)
- ⚡ Incremental Load
- 📦 Master Package
- 📅 Date Dimension
- 🔍 Lookup Transformations
- ✅ Data Validation

---

## 📊 Project Statistics

| Metric | Value |
|---------|------:|
| Transactions | **845,905+** |
| Customer Accounts | **20,000+** |
| ATM Records | **1,569** |
| Transaction Types | **4** |

---

## 🛠️ Technologies Used

- Microsoft SQL Server
- SQL Server Integration Services (SSIS)
- T-SQL
- ETL
- Data Warehouse
- Star Schema
- Power BI

---

## ⭐ Data Warehouse Architecture

<p align="center">
  <img width="1000" alt="Star Schema" src="https://github.com/user-attachments/assets/8b56b256-dd29-4746-90cd-0adb3c6f1377" />
</p>

---

## ⚙️ ETL Workflow

```text
OLTP Database
        │
        ▼
SQL Server
        │
        ▼
SSIS ETL Packages
        │
        ▼
Dimensions
        │
        ▼
FactTransaction
        │
        ▼
Power BI Dashboard
```

---

# 📷 Project Screenshots

## Database Diagram

<p align="center">
  <img width="1000" alt="Database Diagram" src="https://github.com/user-attachments/assets/8b56b256-dd29-4746-90cd-0adb3c6f1377" />
</p>

---

## Master Package

<p align="center">
  <img width="1000" alt="Master Package" src="https://github.com/user-attachments/assets/a6d4f257-c99c-4749-b1c7-c208f0f23ff0" />
</p>

---

## Fact Transaction ETL

<p align="center">
  <img width="700" alt="Fact ETL" src="https://github.com/user-attachments/assets/135c74f9-2823-472f-bd9a-63272e344015" />
</p>

---

## Power BI Dashboard

<p align="center">
  <img width="1000" alt="Power BI Dashboard" src="https://github.com/user-attachments/assets/7834998f-3352-4bcf-8994-ec615e8136f1" />
</p>

---

## 📁 Project Structure

```text
Banking-DataWarehouse-ETL
│
├── SQL Scripts
├── SSIS Packages
├── Database Diagram
├── Dashboard
├── Images
└── README.md
```

---

## 📈 Future Improvements

- Azure Data Factory (ADF)
- dbt
- Microsoft Fabric
- PySpark
- CI/CD Pipeline
- Azure Data Lake

---

## 👨‍💻 Author

**Abdallah Moataz**

- LinkedIn: https://www.linkedin.com/in/abdallahelsobkyy
---

## ⭐ If you found this project useful, don't forget to give it a Star!
