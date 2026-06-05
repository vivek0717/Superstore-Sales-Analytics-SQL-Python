# Superstore Sales Analytics – SQL & Python

<p align="center">
  <img src="https://img.shields.io/badge/Python-Data%20Analytics-blue?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/SQL-Window%20Functions-orange?style=for-the-badge&logo=postgresql" />
  <img src="https://img.shields.io/badge/Machine%20Learning-K--Means-green?style=for-the-badge&logo=scikitlearn" />
  <img src="https://img.shields.io/badge/Forecasting-ARIMA-purple?style=for-the-badge&logo=plotly" />
</p>

<p align="center">
  <b>End-to-end sales analytics project using Python, SQL, EDA, customer segmentation, and time-series forecasting.</b>
</p>

---

## Project Overview

This project analyzes the **Superstore Sales Dataset** to uncover business insights from raw retail transaction data. The workflow covers **data cleaning, SQL analysis, exploratory data analysis, customer segmentation using RFM + K-Means, and sales forecasting using ARIMA**. The Power BI step was intentionally skipped in this version so the project focuses on the analytics pipeline first.

### What this project includes

- Data ingestion and cleaning in **Python (Pandas)**
- Business analysis in **SQL** using aggregates and window functions
- **EDA** with visualizations in Matplotlib and Seaborn
- **RFM customer segmentation**
- **K-Means clustering** for customer grouping
- **ARIMA forecasting** for future sales trend analysis

---

## Workflow

```text
Raw CSV Dataset
      ↓
Data Cleaning with Python
      ↓
SQL Analysis and KPI Queries
      ↓
EDA and Visualization
      ↓
RFM + K-Means Customer Segmentation
      ↓
ARIMA Sales Forecasting
      ↓
GitHub Documentation
```

---

## Key Highlights

### Data Cleaning
- Standardized column names to `snake_case`
- Converted date columns into proper datetime format
- Removed unnecessary fields like row identifiers
- Prepared clean data for analysis

### SQL Analysis
- Calculated overall KPIs such as sales, profit, orders, and customers
- Analyzed region-wise and category-wise sales performance
- Identified top products and top customers
- Used **window functions** for rankings and running totals

### EDA with Python
- Analyzed sales by category, sub-category, and region
- Visualized monthly sales trends
- Studied relationships between sales, profit, discount, and quantity
- Built charts for business insight storytelling

### Advanced Analytics
- Built **RFM (Recency, Frequency, Monetary)** features
- Applied **K-Means clustering** to segment customers
- Labeled clusters into business-friendly customer groups
- Built **ARIMA model** for 6-month sales forecasting

---

## Tech Stack

| Area | Tools Used |
|------|------------|
| Programming | Python |
| Data Handling | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| SQL | Oracle SQL / Advanced SQL |
| Machine Learning | Scikit-learn |
| Forecasting | Statsmodels (ARIMA) |
| Notebook Environment | Jupyter / Google Colab |
| Version Control | Git & GitHub |

---

## Repository Structure

```bash
superstore-sales-analytics/
│
├── README.md
├── requirements.txt
├── data/
│   └── superstore_clean.csv
├── notebooks/
│   └── superstore.ipynb
├── sql/
│   └── Sql-Queries.txt
├── reports/
│   └── project-images-or-plots
```

---

## Business Questions Answered

- Which regions generate the highest sales and profit?
- Which categories and sub-categories perform best?
- Who are the most profitable customers?
- What are the top-selling products?
- How do monthly sales change over time?
- Can customers be grouped into meaningful segments?
- What do future sales trends look like?

---

## Why this project matters

This project demonstrates a complete analytics workflow that recruiters often look for in data analytics roles:

- Turning raw data into structured analysis
- Writing practical business SQL queries
- Building visual EDA reports
- Applying machine learning for segmentation
- Using forecasting for decision support
- Presenting the work professionally on GitHub

---

## Author

**Vivek Parmar**  
Aspiring Data Analyst | Business Intelligence Enthusiast | SQL, Python, Power BI

