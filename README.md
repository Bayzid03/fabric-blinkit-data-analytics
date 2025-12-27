# 🛒 Fabric Blinkit Data Analytics

[![Microsoft Fabric](https://img.shields.io/badge/Microsoft_Fabric-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)](https://www.microsoft.com/fabric)
[![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![Dataflow Gen2](https://img.shields.io/badge/Dataflow_Gen2-00BCF2?style=for-the-badge&logo=microsoft&logoColor=white)](https://learn.microsoft.com/fabric)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

> **End-to-end analytics solution for Blinkit grocery data using Microsoft Fabric Lakehouse, Dataflow Gen2, and Power BI with custom DAX calculations and interactive dashboards.**

---

## 🎯 Project Overview

Built a complete business intelligence solution for Blinkit (Indian grocery delivery platform) using Microsoft Fabric. Ingested raw data into Lakehouse, transformed it using Dataflow Gen2, created semantic models with DAX calculations, and delivered interactive Power BI dashboards.

**Key Achievements:**
- 📊 Built **Power BI dashboards** with 4 KPI metrics (Total Sales, Avg Sales, Items, Ratings)
- 🔄 Automated **Dataflow Gen2 pipeline** for data transformation
- 📐 Created **semantic model** with DAX measures
- ⚡ Delivered **actionable insights** on sales and product performance

---

## 🏗️ Architecture

```
Blinkit Dataset → Lakehouse → Dataflow Gen2 → Semantic Model → Power BI
   (Raw CSV)      (Storage)   (Transform)      (DAX Calcs)    (Dashboard)
```

| Component | Purpose | Technology |
|-----------|---------|------------|
| **Lakehouse** | Raw data storage | Fabric Lakehouse |
| **Dataflow Gen2** | ETL & data cleaning | Power Query (M) |
| **Semantic Model** | Business calculations | DAX Measures |
| **Power BI** | Interactive dashboards | Power BI Service |

---

## ✨ Key Features

### 📊 Core KPI Metrics
- **Total Sales**: Sum of all sales transactions
- **Average Sales**: Mean sales value per transaction
- **Number of Items**: Total product count in catalog
- **Average Rating**: Mean customer rating across products

### 🔄 Data Pipeline
- Data ingestion from CSV to Fabric Lakehouse
- Dataflow Gen2 for cleaning and quality checks
- Semantic model with star schema design
- Power BI reports with interactive visuals

### 📈 Dashboard Components
- Sales performance analytics
- Product insights and ratings
- Category-wise breakdowns
- Interactive filters and drill-throughs

---

## 📐 Implementation Steps

**1. Requirements Gathering** → Defined KPIs and business needs  
**2. Data Walkthrough** → Analyzed Blinkit dataset structure  
**3. Data Connection** → Ingested CSV into Lakehouse  
**4. Data Cleaning** → Quality checks via Dataflow Gen2  
**5. Data Modeling** → Built star schema relationships  
**6. Data Processing** → Applied transformations  
**7. DAX Calculations** → Created measures (Total Sales, Avg Sales, etc.)  
**8. Dashboard Layout** → Designed report structure  
**9. Chart Development** → Built visualizations  
**10. Insights Generation** → Extracted business intelligence  

---

## 📊 Dashboard Preview

### Blinkit Sales & Performance Dashboard

<img width="1098" height="705" alt="image" src="https://github.com/user-attachments/assets/b85e02d0-10d2-4d45-8780-2d1759c37bda" />


**Key Metrics:**
- 💰 Total Sales Performance
- 📦 Product Catalog Size
- ⭐ Customer Rating Score
- 📈 Sales Trends & Distribution

---

## 🚀 Quick Start

### Prerequisites
- Microsoft Fabric workspace
- Power BI Desktop
- Blinkit grocery dataset (CSV)

### Setup Steps
1. **Create Fabric Workspace** → Enable Lakehouse
2. **Upload Data** → Load CSV to Lakehouse
3. **Build Dataflow Gen2** → Clean and transform data
4. **Create Semantic Model** → Add DAX measures
5. **Develop Dashboard** → Build Power BI visuals
6. **Publish Report** → Deploy to Fabric workspace

---

---

## 📈 Key Insights

- 💰 **Total Revenue**: Comprehensive sales tracking
- 📦 **Inventory Coverage**: Full product catalog analysis
- ⭐ **Quality Metrics**: Customer satisfaction scores
- 📊 **Performance Trends**: Time-series sales patterns
- 🎯 **Category Analysis**: Top-performing product segments

---

## 🎓 Skills Demonstrated

- **Microsoft Fabric**: Lakehouse, Dataflow Gen2, workspace management
- **Data Engineering**: ETL pipelines, data cleaning, quality checks
- **Data Modeling**: Star schema, relationships, optimization
- **DAX**: Measures, calculations, time intelligence
- **Power BI**: Dashboard design, visualizations, interactive reporting
- **Business Intelligence**: KPI definition, insight generation

---

## 📫 Contact
 
📧 Email: hossainbayzid011@gmail.com  

---

## 📄 License

MIT License

---

<div align="center">

**⭐ Star this repo if you found it helpful!**

Built with Microsoft Fabric & Power BI

</div>
