# 🚀 Lenskart Snowflake ETL Pipeline

Production-grade data engineering pipeline designed to ingest, validate, and load large-scale e-commerce telemetry data into a cloud data warehouse.

## 📊 Project Overview
This project simulates an enterprise-level data workflow: connecting Python to **Snowflake**, performing robust handling using **Pandas**, and bulk-loading over **150,000 verified rows** of retail telemetry into a cloud relational database.

## 🛠️ Tech Stack & Architecture
* **Language:** Python, SQL
* **Environment:** Google Colab / Jupyter Notebook (`.ipynb`)
* **Cloud Data Warehouse:** Snowflake (`REALTIME_ECOMMERCE_DB`)
* **Core Libraries:** `snowflake-connector-python`, `pandas`, `snowflake.connector.pandas_tools`

## 📂 Repository Structure
* `lenskart_snowflake_etl.ipynb`: Interactive pipeline notebook detailing extraction, connection management, data validation, and high-performance bulk insertion.
* `schema.sql`: Database architecture blueprint defining target databases, schemas, and raw telemetry tables.

## 📈 Key Pipeline Metrics
* **Total Volume Processed:** 150,000+ records
* **Performance Optimization:** Leveraged `write_pandas` for high-speed cloud ingestion, eliminating row-by-row bottlenecks.

---
*Built as a portfolio project showcasing modern data stack implementation.*
