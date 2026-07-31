# 🏨 Hotel Booking Data Engineering Project using Snowflake

## 📌 Project Overview

This project demonstrates an end-to-end Data Engineering pipeline built using Snowflake. It simulates a Hotel Booking System where booking data is ingested from CSV files, transformed through multiple layers, and converted into business-ready analytics.

The project follows a Medallion Architecture with separate **RAW**, **CURATED**, and **ANALYTICS** schemas to ensure data quality, maintainability, and efficient business reporting.

---

## 🚀 Technologies Used

- Snowflake
- SQL
- CSV Files
- ETL Concepts
- Data Warehousing
- GitHub

---

## 🏗️ Project Architecture

```text
CSV Files
      │
      ▼
Internal Stage
      │
      ▼
COPY INTO
      │
      ▼
RAW Schema
      │
      ▼
CURATED Schema
      │
      ▼
ANALYTICS Schema
      │
      ▼
Business Reports
```

---

## 📂 Repository Structure

```text
Hotel-Booking-Data-Engineering/
│
├── Dataset/
│   ├── customer.csv
│   ├── hotel.csv
│   ├── rooms.csv
│   ├── booking.csv
│   └── payment.csv
│
├── SQL_Scripts/
│   └── Hotel_Booking_Project.sql
│
├── Screenshots/
│   ├── Project setup screenshots
│   ├── Database structure
│   ├── Data loading
│   ├── Verification
│   └── Analytics output
│
├── Documentation/
│   └── Project_Documentation.docx
│
└── README.md
```

---

## ⚙️ Project Workflow

1. Created a Snowflake Virtual Warehouse.
2. Created the database and schemas (RAW, CURATED, and ANALYTICS).
3. Designed relational tables with primary and foreign key constraints.
4. Created an Internal Stage for CSV file ingestion.
5. Uploaded datasets into Snowflake.
6. Loaded data using the `COPY INTO` command.
7. Validated successful data loading using SQL queries.
8. Built the CURATED layer for clean and structured data.
9. Generated business reports using SQL queries in the ANALYTICS layer.

---

## 📊 Datasets Used

| Dataset | Description |
|----------|-------------|
| customer.csv | Customer information |
| hotel.csv | Hotel details |
| rooms.csv | Room information |
| booking.csv | Booking transaction details |
| payment.csv | Payment transaction details |

---

## 🗄️ Database Objects

### Warehouse

- `HOTEL_WH`

### Database

- `HOTEL_BOOKING_DB`

### Schemas

- RAW
- CURATED
- ANALYTICS

### RAW Tables

- CUSTOMER
- HOTEL
- ROOM
- BOOKING
- PAYMENT

---

## 📈 Business Analytics

The project generates business insights including:

- Hotel-wise booking summary
- Revenue analysis
- Room type analysis
- Payment summary
- Booking statistics
- Customer booking reports

---

## 📸 Project Screenshots

All project execution screenshots—including project setup, database creation, table creation, CSV upload, data loading, verification, and analytics outputs—are available in the **Screenshots** folder of this repository.

---

## 🌟 Key Features

- End-to-End Data Engineering Pipeline
- Medallion Architecture (RAW → CURATED → ANALYTICS)
- Snowflake Internal Stage for data ingestion
- SQL-based ETL implementation
- Data validation using SQL
- Business analytics and reporting
- Well-organized GitHub project structure

---

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Snowflake Data Warehousing
- SQL Development
- Internal Stages
- COPY INTO Data Loading
- Data Validation
- Schema Design
- ETL Concepts
- Business Analytics
- GitHub Project Documentation

---

## 🚀 Future Enhancements

- Automate data ingestion using Snowpipe.
- Integrate Apache Airflow for workflow orchestration.
- Build interactive dashboards using Power BI or Tableau.
- Implement role-based access control.
- Support real-time data ingestion.

---

## 👩‍💻 Author

**Sai Devi Mahalakshmi Kattamuri**

**Programmer Analyst Trainee**

### Skills

- Snowflake
- SQL
- Azure Data Engineering
- Python
- ETL
- Data Warehousing

---

⭐ **If you found this project useful, consider giving it a Star!**
