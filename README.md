# 🏗️ E-Commerce Medallion Data Pipeline (Databricks + PySpark)

An end-to-end Lakehouse-based E-Commerce analytics solution built using a **Medallion Architecture (Bronze → Silver → Gold)** in Databricks.  
The project processes raw transactional CSV data into a curated gold-layer fact model powering interactive Tableau dashboards.

---

## 🚀 Project Overview

This project demonstrates a scalable data engineering workflow:

- Ingestion of 30+ transactional CSV files
- Bronze layer raw data storage
- Silver layer cleansing & standardization
- Gold layer dimensional modeling
- Denormalized fact view for BI consumption
- Interactive Tableau dashboards for business insights

The pipeline follows modern **Lakehouse best practices** using PySpark transformations and structured layering.

---

## 🏛️ Architecture

The project implements a Medallion Architecture to progressively refine data quality and analytical readiness.

<p align="center">
  <img src="Architecture/Architectural Diagram.png" width="700">
</p>

### 🔹 Bronze
- Ingested 30+ raw transactional CSV files into the Lakehouse  
- Applied schema validation and structured data storage  
- Preserved source-level granularity for traceability and auditability  

### 🔹 Silver
- Performed data cleansing, type casting, and integrity checks  
- Standardized currency values into INR for unified revenue analysis  
- Removed duplicates and enforced business validation rules  
- Structured refined datasets for downstream analytical modeling  

### 🔹 Gold
- Designed star-schema aligned dimension and fact tables  
- Engineered consolidated fact views optimized for analytical queries  
- Pre-computed key business metrics (Revenue, AOV, Discount Impact)  
- Prepared BI-ready datasets for high-performance dashboard consumption   

---

## 📊 Tableau Dashboards

🔗 **Live Dashboard:**  
[View on Tableau Public]([PASTE_YOUR_LIVE_LINK_HERE](https://public.tableau.com/views/Book1_17709891109510/REVENUE?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link))

The gold-layer dataset powers business-facing dashboards focused on revenue, product performance, and geographic insights.

### Executive Revenue Overview
<p align="center">
  <img src="Dashboards/REVENUE Dashboard.png" width="700">
</p>

### Product Performance Analysis
<p align="center">
  <img src="Dashboards/PRODUCTS Dashboard.png" width="700">
</p>

### Customer & Geographic Insights
<p align="center">
  <img src="Dashboards/GEO Dashboard.png" width="700">
</p>

---

## 🛠️ Tech Stack

- Databricks
- PySpark
- Delta Lake
- SQL
- Tableau

---

## 📌 Key Highlights

- Implemented full Bronze–Silver–Gold transformation pipeline  
- Designed gold-layer fact & dimension tables  
- Built denormalized analytical view for BI efficiency  
- Calculated business KPIs (Revenue, AOV, Discount Impact)  
- Delivered stakeholder-ready dashboards  

---

Sahil Chakaraborty ✨
