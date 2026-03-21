# Databricks ETL Pipeline – Medallion Architecture

## 📌 Overview

This project implements an end-to-end data pipeline using Databricks and PySpark following the Medallion Architecture (Bronze → Silver → Gold).

It demonstrates how raw data is ingested, cleaned, and transformed into analytics-ready datasets.

---

## 🧱 Architecture

Bronze Layer → Raw data ingestion from CSV files
Silver Layer → Data cleaning, transformation, and validation
Gold Layer → Business-level aggregations and KPIs

---

## ⚙️ Technologies Used

* Databricks
* PySpark
* Delta Lake
* SQL
* Python

---

## 🚀 Features

* Scalable ETL pipeline
* Metadata-driven ingestion
* Data quality checks (null validation)
* Logging for monitoring
* Incremental data processing
* Delta Lake storage

---

## 📂 Project Structure

notebooks/

* 01_bronze_ingestion.py
* 02_silver_transformation.py
* 03_gold_analytics.py

config/

* ingestion_config.py

---

## 📊 Example KPI

* Total revenue by product
* Total number of orders
* Average order value

---

## ▶️ How to Run

1. Run Bronze ingestion notebook
2. Run Silver transformation notebook
3. Run Gold analytics notebook

---

## 🎯 Key Learnings

* Implementation of Medallion Architecture
* Building scalable data pipelines
* Data quality validation
* Incremental data processing

---

## 👤 Author

Malick Hamidou Boureima

