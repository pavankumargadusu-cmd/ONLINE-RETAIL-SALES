# Online Retail Sales & Revenue Loss Analytics

An end-to-end data analytics project analyzing **525,000+ online retail transactions** to uncover revenue trends, customer purchasing behavior, product performance, and cancellation anomalies using **Python**, **SQL**, and **Power BI**.

---

## Project Overview

In retail transaction datasets, cancelled orders and negative-quantity entries often skew revenue metrics if deleted outright or left unseparated. Rather than discarding anomalous records during data cleaning, this pipeline **isolates valid sales and cancelled transactions into separate analytical tables**—preserving full visibility into revenue leakage and return patterns while keeping core sales metrics accurate.

---

## Repository Contents

| File | Description |
| :--- | :--- |
| `online_retail_II.xlsx` | Raw retail transaction dataset (525,000+ records) |
| `onlineretail.ipynb` | Jupyter Notebook containing ETL data cleaning, validation, and dataset splitting in Python |
| `sales.csv` | Cleaned dataset containing valid completed sales transactions |
| `cancellations.csv` | Isolated dataset containing cancelled orders and negative-quantity anomalies |
| `online_retail.pbix` | Multi-page interactive Power BI dashboard analyzing revenue, sales trends, and cancellations |

---

## Methodology & Workflow

1. **Data Cleaning & Anomaly Isolation (Python / Pandas):**
   - Handled missing customer IDs, standardized data types, and removed duplicate entries.
   - Separated records into `sales.csv` (valid positive transactions) and `cancellations.csv` (cancelled invoices and negative-quantity records) so revenue losses can be tracked independently without distorting net sales KPIs.
2. **Exploratory & Revenue Analysis (SQL / Python):**
   - Evaluated total revenue, order volume, average order value, seasonal sales peaks, top-performing SKUs, and cancellation rates by product and region.
3. **Interactive Dashboarding (Power BI):**
   - Built a multi-page interactive report (`online_retail.pbix`) enabling drill-down filtering across time periods, countries, product categories, and cancellation impact.

---

## How to Use

1. **Explore the ETL Notebook:** Open `onlineretail.ipynb` in Jupyter Notebook or VS Code to review the data cleaning and transformation logic.
2. **Interact with the Dashboard:** Download `online_retail.pbix` and open it in **Power BI Desktop** to explore the visual reports and slicers.

---

## Author

**Pavan Kumar Gadusu**  
[GitHub Profile](https://github.com/pavankumargadusu-cmd)
