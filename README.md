# 🏨 Hotel Booking Data Engineering Project using Snowflake

## 📌 Project Overview

This project demonstrates an end-to-end Data Engineering pipeline built using Snowflake. The project simulates a Hotel Booking System where booking data is ingested from CSV files, transformed through multiple layers, and converted into business-ready analytics.

The project follows a modern Medallion-style architecture with separate **RAW**, **CURATED**, and **ANALYTICS** schemas to ensure data quality and support business reporting.

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
```

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

