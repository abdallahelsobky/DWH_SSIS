# 🏦 Banking Data Warehouse & ETL Project

An end-to-end Banking Data Warehouse project built using **SQL Server** and **SQL Server Integration Services (SSIS)** as part of my Data Engineering learning journey.

---

## 📌 Project Overview

This project demonstrates how to design and implement a complete ETL pipeline that extracts banking data from an OLTP database, transforms it, and loads it into a Star Schema Data Warehouse for reporting and analytics.

---

## 🚀 Features

- Star Schema Design
- ETL Pipeline using SSIS
- Slowly Changing Dimension (SCD Type 2)
- Incremental Load
- Master Package
- Date Dimension
- Lookup Transformations
- Data Validation

---

## 📊 Project Statistics

| Metric | Value |
|---------|------:|
| Transactions | **845,905+** |
| Customer Accounts | **20,000+** |
| ATM Records | **1,569** |
| Transaction Types | **4** |

---

## 🛠 Technologies

- SQL Server
- SQL Server Integration Services (SSIS)
- SQL
- ETL
- Data Warehousing
- Star Schema

---

## ⭐ Data Warehouse Architecture

<p align="center">
<img src="Images/StarSchema.png" width="900">
</p>

---

## ⚙ ETL Workflow

```
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

## 📷 Screenshots

### Database Diagram

"<img width="1251" height="782" alt="DWH" src="https://github.com/user-attachments/assets/8b56b256-dd29-4746-90cd-0adb3c6f1377" />">

---

### Master Package

"<img width="1105" height="604" alt="Screenshot 2026-07-04 061011" src="https://github.com/user-attachments/assets/a6d4f257-c99c-4749-b1c7-c208f0f23ff0" />">

---

### Fact ETL

"<img width="772" height="577" alt="Screenshot 2026-07-04 060747" src="https://github.com/user-attachments/assets/135c74f9-2823-472f-bd9a-63272e344015" />">

---

### Dashboard

"<img width="1536" height="1024" alt="ChatGPT Image Jul 4, 2026, 06_20_27 AM" src="https://github.com/user-attachments/assets/7834998f-3352-4bcf-8994-ec615e8136f1" />
">

---

## 📁 Project Structure

```
SQL Scripts
SSIS Packages
Database Diagram
Dashboard
Images
```

---

## 📈 Future Improvements

- Azure Data Factory
- dbt
- Microsoft Fabric
- PySpark
- CI/CD Pipeline

---

## 👨‍💻 Author

**Abdallah Moataz**

LinkedIn:
(https://www.linkedin.com/in/abdallahelsobkyy?utm_source=share_via&utm_content=profile&utm_medium=member_ios)

