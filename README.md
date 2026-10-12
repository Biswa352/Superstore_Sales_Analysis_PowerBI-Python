
# 📊 Superstore Sales Dashboard – Power BI + Python Integration

## 👤 Author
**Biswarup Das**

## 📌 Project Overview

This project presents an **interactive sales dashboard** built using **Power BI**, with **Python** integration for data preprocessing and advanced visuals.

An interactive Power BI dashboard exploring sales performance across regions, product categories, and months using the Sample Superstore dataset. A Python visual built with Matplotlib compares average sales per order line by category.

---

## 🛠 Tools Used

- 📘 **Power BI Desktop**
- 🐍 **Python (Pandas, Matplotlib)** *(used inside Power BI)*
- 📁 Dataset: `Sample - Superstore.csv`
- 💡 Data Source: [Kaggle – Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

---

## Python visual in Power BI (via Python Script)

-The report includes a Python visual built with Matplotlib. It groups the data by `Category` and calculates the **mean of `Sales` per order line**. The result complements the category-total visual by showing a different metric: average sales per row rather than total sales.

-`Row ID` is included in the Python visual's field inputs so Power BI's generated Python input table retains row-level records rather than collapsing identical combinations of selected fields before the script runs.

-Used **Python script inside Power BI** to clean the dataset and create a new `MonthYear` column for time-series analysis.

🔹 Implemented via:
> **Home → Get Data → Python script**

---

## 📈 Visualizations in Power BI

| Visualization | Purpose |
|---------------|---------|
| 📉 Line Chart | Show **monthly sales trend** using `MonthYear` |
| 📊 Bar Chart | Compare **sales by Region** |
| 🍩 Donut Chart | Breakdown of **sales by Category** |
| 📦 Card Visuals | Show total sales in selected filters |
| 🧮 Python Visual | Custom bar chart created using Matplotlib |
| 🎛 Slicers | Filters by Region & Category |

---

## Dashboard Overview

The Power BI report includes:
- Sales performance across the four regions
- Sales contribution by product category
- Monthly sales trends
- A Python visual comparing average sales per order line across categories

---

## 📊 Key Insights

- **West** is the highest-performing region, with sales of approximately **$0.73M**.
- **Technology** is the leading category by total sales, at approximately **$836.15K**.
- **November** records the highest monthly sales, at approximately **$352.46K**, while **February** records the lowest, at approximately **$59.75K**.
- In the Python visual, **Technology has the highest average sales per order line** among the three categories.

These findings describe the patterns visible in the report; they do not establish the causes behind those patterns.

---

## 📦 Deliverables

- `Sample_Superstore.csv` — source dataset
- `Superstore_Cleaned.xls` — cleaned workbook used in the project
- `Superstore-PowerBI_Analysis.ipynb` | Python notebook used for data preparation, including date processing and creation of the `MonthYear` field for time-series analysis
- `Superstore_Dashboard.pbix` – Power BI file with all visuals
- `dashboard_screenshot.png` – Visual export of dashboard
- `Insights.txt` – Business observations based on the dashboard
- `README.md` – Project documentation (this file)
- `LICENSE` – MIT License

---

## How to View the Report

1. Download `Superstore_Sales.pbix` from this repository.
2. Open it in Power BI Desktop.
3. If Power BI prompts for a data-source location, update the source path to match where the project data files are stored.

---

## 📄 License

This project is open source under the **MIT License**.  
See the [LICENSE](./LICENSE) file for more details.

---

## 📬 Contact

Have suggestions, feedback, or want to collaborate?  
Reach out to **Biswarup Das** via GitHub or LinkedIn.

---
