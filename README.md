# 🚀 End-to-End Data Engineering Pipeline (Medallion Architecture)

## 📌 Project Overview

This project demonstrates a real-world **Data Engineering ETL pipeline** built using **PySpark**, following the **Medallion Architecture (Bronze → Silver → Gold)** approach.

The pipeline processes raw data from multiple sources (CRM and ERP systems), performs data cleaning and transformations, and produces a final consolidated dataset for analytics and reporting.

---

## 🏗️ Architecture

The pipeline is divided into three layers:

### 🥉 Bronze Layer (Raw Data Ingestion)

* Ingests raw data from source systems
* Stores data in its original format
* No transformations applied

### 🥈 Silver Layer (Data Cleaning & Transformation)

* Cleans and standardizes data
* Handles missing values and inconsistencies
* Separate processing for:

  * CRM data
  * ERP data

### 🥇 Gold Layer (Business-Ready Data)

* Combines CRM and ERP datasets
* Applies business logic and aggregations
* Produces final structured data for reporting

---

## 🔧 Tech Stack

* Python
* PySpark
* SQL
* Databricks / Spark Environment

---

## 📂 Project Structure

```
data-engineering-etl-pipeline/
│
├── notebooks/
│   ├── bronze_layer.ipynb
│   ├── silver_crm.ipynb
│   ├── silver_erp.ipynb
│   ├── gold_layer.ipynb
│
├── screenshots/
├── README.md
├── requirements.txt
```

---

## 🔄 Data Flow

1. Raw data is ingested into the **Bronze layer**
2. Data is cleaned and transformed in the **Silver layer**
3. Final datasets are created in the **Gold layer** for analytics

---

## ⚙️ Key Features

* End-to-end ETL pipeline design
* Multi-source data integration (CRM + ERP)
* Data cleaning and transformation using PySpark
* Layered architecture (Bronze, Silver, Gold)
* Scalable and modular pipeline structure

---

## 📊 Business Use Case

Organizations often receive data from multiple systems such as CRM and ERP.
This project simulates how a data engineer builds a pipeline to:

* Standardize data across systems
* Ensure data quality and consistency
* Deliver a unified dataset for reporting and decision-making

---

## ▶️ How to Run

1. Install dependencies:

```
pip install pyspark
```

2. Open notebooks in:

* Jupyter Notebook / VS Code
* Databricks (recommended)

3. Run notebooks in order:

* Bronze → Silver CRM → Silver ERP → Gold

---

## 📸 Screenshots

<img width="1167" height="665" alt="image" src="https://github.com/user-attachments/assets/8dc6817d-b05c-4ae9-9505-b48670ff92dc" />


---

## 💡 Future Improvements

* Add automated scheduling (Airflow)
* Integrate with cloud storage (AWS / Azure)
* Implement data quality checks and logging

---

## 🔗 Author

Aspiring Data Engineer with hands-on experience in building ETL pipelines, data transformation, and large-scale data processing using PySpark.
