# Retail Store Chain Sales Analysis

This project simulates a **retail chain business analyst** role: I load, clean, and analyze sales data, then build a **Power BI dashboard** for store‑level KPIs.

## Tools used
- SQL (PostgreSQL)
- Power BI
- Excel (data validation)
- Python (data cleaning)
- Git

## Business context
A retail chain wants to:
- Compare store performance by region, category, and month.
- Identify top‑performing and underperforming stores.
- Track trends in sales and returns.

## Files included
- `data/`: Raw CSV files (`store_sales.csv`, `stores.csv`).
- `sql/`: Create tables, load data, and KPI queries.
- `python/`: Data cleaning script (`data_cleaning.py`).
- `excel/`: Excel file for quick checks (`store_sales_clean.xlsx`).
- `powerbi/`: Power BI dashboard file (`.pbix`).
- `docs/`: Business requirements (`business_requirements.md`).

## How to use
1. Run SQL scripts on your local PostgreSQL DB.
2. Connect Power BI to the database.
3. Open `store_sales_clean.xlsx` for sanity checks.
4. Explore the dashboard and test filters (store, month, category).
