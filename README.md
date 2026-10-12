
# 📊 Superstore Sales Dashboard – Power BI + Python Integration

## 👤 Author
**Biswarup Das**

## 📌 Project Overview

This project presents an interactive sales dashboard built with Power BI using the Sample Superstore dataset. It explores sales performance across regions, product categories, and a chronological monthly trend from 2014 to 2017. A custom Python visual built with Matplotlib compares average sales per order line across product categories.

---

## 🛠 Tools Used

- 📘 **Power BI Desktop**
- 🐍 **Python (Pandas, Matplotlib)** *(used inside Power BI)*
- 📁 Dataset: `Sample_Superstore.csv`
- 💡 Data Source: [Kaggle – Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

---

## Python visual in Power BI (via Python Script)

-##Data Preparation

The project includes a Python notebook, Superstore-PowerBI_Analysis.ipynb, intended for data preparation, including date processing and creation of the MonthYear field for time-series analysis.

-##Custom Python Visual

A Python visual built with Matplotlib compares average sales per order line across Furniture, Office Supplies, and Technology. The visual calculates the mean of Sales grouped by Category, complementing the dashboard's category-total chart.

Row ID is included in the Python visual's input fields to help preserve row-level records in the dataset passed to the script by Power BI.

The Python visual is configured within Power BI Desktop using the Python visual in the Visualizations pane.

---

## 📈 Visualizations in Power BI

| Visualization | Purpose |
|---------------|---------|
| 📉 Line Chart | Show **monthly sales trend** using `MonthYear` |
| 📊 Bar Chart | Compare **sales by Region** |
| 🍩 Donut Chart | Breakdown of **sales by Category** |
| 🧮 Python Bar Chart | Compare average sales per order line by category |

---

## Dashboard Overview

The Power BI report includes:
- Sales performance across the four regions
- Sales contribution by product category
- Monthly sales trends
- A Python visual comparing average sales per order line across categories

---

## 📊 Key Insights

- West is the highest-performing region, with sales of approximately $0.73M.
- Technology is the leading category by total sales, at approximately $836.15K, representing 36.4% of the displayed category sales.
- Regional sales vary, with East at approximately $0.68M, Central at $0.50M, and South at $0.39M.
- The chronological monthly sales chart shows substantial variation across the 2014–2017 period, with several peaks and declines.
- In the Python visual, Technology has the highest average sales per order line among the three categories.

These observations describe the patterns visible in the dashboard; they do not establish the causes behind those patterns.

---

## 📦 Deliverables

- `Sample_Superstore.csv` — source dataset
- `Superstore_Cleaned.xls` — cleaned workbook used in the project
- `Superstore-PowerBI_Analysis.ipynb` | Python notebook used for data preparation, including date processing and creation of the `MonthYear` field for time-series analysis
- `Superstore_Sales.pbix` — Power BI report with all visuals
- `Superstore Sales PowerBI Python Analysis.png` – Visual export of dashboard
- `Superstore Sales Insights.txt` – Business observations based on the dashboard
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
