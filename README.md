End-to-end Vendor Performance Analysis using Python, SQL, and Power BI to evaluate vendor contributions, purchasing trends, profitability, and inventory performance.
# Vendor Performance Analysis | Python, SQL & Power BI

## Project Overview

The **Vendor Performance Analysis** project is an end-to-end data analytics solution designed to evaluate vendor performance, analyze purchasing and sales trends, and generate actionable insights to support procurement and inventory management decisions.

The project uses Python for data ingestion, cleaning, exploratory data analysis, and analytical processing, SQL for data querying and aggregation, and Microsoft Power BI for interactive data visualization and reporting.

The primary objective is to identify high-performing vendors, analyze purchasing patterns, evaluate vendor contributions, and identify opportunities to improve procurement efficiency and inventory management.

## Business Objectives

- Analyze vendor-wise purchasing and sales performance.
- Identify top-performing vendors and brands.
- Evaluate vendor contribution to overall business performance.
- Analyze purchase prices, inventory levels, and sales trends.
- Identify low-performing vendors and potential improvement areas.
- Analyze unsold inventory and capital tied up in stock.
- Support data-driven procurement and vendor management decisions.

## Technology Stack

| Technology | Purpose |
|---|---|
| Python | Data ingestion, preprocessing and analysis |
| Pandas & NumPy | Data manipulation and transformation |
| SQL | Data querying, aggregation and analysis |
| Jupyter Notebook | Exploratory data analysis and analytical development |
| Microsoft Power BI | Interactive dashboards and visualization |
| CSV | Source data storage |

## Project Architecture

The project follows a structured data analytics workflow:

1. **Data Ingestion:** Import source CSV files into the analytical database using Python.
2. **Data Exploration:** Examine datasets, identify data-quality issues and understand underlying business patterns.
3. **Data Processing:** Clean, transform and aggregate data using Python and SQL.
4. **Vendor Analysis:** Calculate vendor-level performance metrics and analyze purchasing and sales contributions.
5. **Data Visualization:** Develop interactive Power BI dashboards to communicate business insights.

## Repository Structure

```text
Vendor-Performance-Analysis/
│
├── EDA.ipynb
│   └── Initial exploratory data analysis
│
├── vendor performance analysis.ipynb
│   └── Detailed vendor analysis, visualizations
│       and analytical outputs
│
├── get_vendor_summary.ipynb
│   └── Vendor summary generation
│
├── ingestion_db.py
│   └── Python-based data ingestion
│
├── ingestion_db.log
│   └── Data ingestion execution logs
│
├── get_vendor_summary.log
│   └── Vendor summary execution logs
│
├── begin_inventory.csv
│   └── Beginning inventory data
│
├── end_inventory.csv
│   └── Ending inventory data
│
├── purchase_prices.csv
│   └── Purchase price information
│
├── Vendor Analysis.pbix
│   └── Power BI dashboard
│
└── README.md
```

## Dataset Description

The project works with multiple datasets related to procurement, inventory, purchasing and sales.

| Dataset | Description |
|---|---|
| begin_inventory | Beginning inventory records |
| end_inventory | Ending inventory records |
| purchases | Purchase transaction records |
| purchase_prices | Product purchase price information |
| sales | Sales transaction records |
| vendor_invoice | Vendor invoice information |
| vendor_sales_summary | Vendor-level sales summary |
| vendpr_sales_summary | Vendor and product-level sales summary |

## Key Analytical Areas

### 1. Exploratory Data Analysis (EDA)
- Dataset structure and statistical analysis.
- Missing value and data-quality examination.
- Distribution and trend analysis.
- Identification of purchasing and sales patterns.

### 2. Vendor Performance Analysis
- Vendor-wise sales and purchase contribution.
- Identification of top-performing vendors.
- Comparison of vendor-level business performance.
- Identification of vendors requiring further evaluation.

### 3. Inventory Analysis
- Beginning versus ending inventory analysis.
- Inventory movement examination.
- Identification of unsold inventory.
- Analysis of capital tied up in inventory.

### 4. Financial and Procurement Analysis
- Purchase value analysis.
- Sales contribution analysis.
- Gross profit and profit margin analysis.
- Brand and vendor contribution analysis.

## Power BI Dashboard

The Power BI dashboard provides an interactive reporting layer for analyzing vendor and procurement performance.

Key analytical areas include:

- Overall sales and purchase performance.
- Vendor contribution and ranking.
- Brand-level performance.
- Gross profit and profit margin.
- Unsold inventory and capital analysis.
- Identification of low-performing vendors.

## Business Value

This project demonstrates how transactional procurement and inventory data can be transformed into meaningful business intelligence.

The resulting analytical framework helps businesses:

- Make informed vendor selection decisions.
- Improve procurement visibility.
- Identify purchasing and inventory inefficiencies.
- Understand vendor and brand profitability.
- Improve inventory management decisions.
- Support strategic supplier evaluation.

## Skills Demonstrated

- Python-based data processing and automation.
- SQL querying and data aggregation.
- Exploratory Data Analysis (EDA).
- Data cleaning and transformation.
- Vendor and procurement analytics.
- Inventory and financial analysis.
- Business Intelligence and Power BI dashboard development.
- Data-driven business decision-making.

---

**Project:** Vendor Performance Analysis  
**Domain:** Procurement Analytics | Supply Chain Analytics | Business Intelligence  
**Tools:** Python | SQL | Microsoft Power BI | Jupyter Notebook


