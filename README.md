# CMS Inpatient Analytics (In Progress)

This project demonstrates a healthcare data analytics workflow using publicly available **CMS inpatient data**. It models a real-world scenario—shifting from SQL Server–style logic to a modern **Databricks + Power BI** pipeline—to build scalable, payer-facing reporting and insights.

## 🔍 Project Purpose

- Simulate a modern healthcare analytics stack using Databricks and Power BI  
- Apply **PySpark** and **SQL** in **Databricks notebooks** to replicate data transformation workflows  
- Build a **Power BI** dashboard using **Power Query** and **DAX**, backed by a **star schema** model  
- Showcase end-to-end skills in **ETL**, **data modeling**, and **visualization** commonly used in migration efforts

## 🧰 Tech Stack

### Databricks
- PySpark (data cleaning, transformation, and aggregation)
- SQL (exploratory queries and validation)
- Notebook workflows (simulated via job orchestration)
- Delta Lake tables (Bronze, Silver, Gold layers)

### Power BI
- Power Query (data ingestion and transformation)
- DAX (calculated fields and measures)
- Interactive dashboards (payer-focused reporting layout)

### Cloud Storage
- AWS S3 (for raw CMS files)

### Data Source
- CMS Inpatient Public Datasets (cleaned and modeled for reporting use cases)

## ⚙️ Workflow Automation (In Progress)

This project includes a simulated Databricks Job Workflow to demonstrate cloud-native orchestration and modular ETL structure.  
Tasks include ingestion, transformation, and summary layers, aligned with a medallion architecture (Bronze → Gold).

> _(Coming soon)_  
- 📸 **[Workflow Screenshot](images/job_screenshot.png)**  
- 🧾 **[YAML-style Summary](job_config_summary.md)**  
- 🧬 **[Full JSON Export](job_definition.json)**

## 📊 Dashboard Output (In Progress)

> _(Coming soon)_  
> Screenshot and public Power BI embed (if applicable) will be added here to demonstrate end-user reporting experience.

## 💡 Real-World Relevance

This project is designed to reflect common patterns in healthcare analytics modernization:
- Replacing legacy SQL Server logic with Databricks notebooks and cloud-based storage
- Creating clean, trusted data models to support visualization tools like Power BI
- Using PySpark and DAX to bridge engineering and reporting layers in a collaborative, Agile environment
