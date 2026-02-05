# Sales Data ETL Pipeline (Python)

## Project Overview

A **lightweight, production-oriented batch-style ETL pipeline** built in Python to process raw sales CSV files, enforce data quality rules, calculate revenue metrics, and generate structured outputs and reports.

The project mirrors **real-world data ingestion workflows**, where incoming data must be validated, cleaned, and summarized before downstream analytics or storage.

---

## Functionality

* Ingests multiple raw CSV files from an input directory
* Applies validation rules to critical business fields
* Drops invalid or incomplete records with tracked reasons
* Computes revenue per valid transaction
* Writes a cleaned master dataset
* Generates an ETL and data quality summary report

---

## Project Structure

```
.
├── incoming/              # incoming raw CSV files
├── processed/
│   └── sales_master.csv   # Cleaned and validated dataset
├── reports/
│   └── etl_report.txt     # ETL & data quality metrics
├── archive/               # Archived source(incoming) files
└── batch_sales_etl_pipeline.py        # Main ETL workflow
```

---

## Pipeline Design Highlights

* Uses Python standard library only (csv, os, datetime)
* Clear separation of validation logic
* Defensive handling of malformed data
* Metrics-driven reporting for data quality

---

## Skills Demonstrated

* Python ETL development
* Data validation & cleansing
* File system automation
* Basic data quality metrics
* Production-style scripting practices
* Ingesting, cleaning and loading multiple raw CSV files 

---

## How to Run

```
python etl_pipeline.py
```

Place raw `.csv` files inside the `incoming/` directory before execution.

---

> This project demonstrates the ability to build **reliable, readable ETL pipelines** that handle messy real-world data while producing traceable outputs and quality metrics—core skills for data engineering.

---
