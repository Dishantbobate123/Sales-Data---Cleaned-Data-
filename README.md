
📌 Project Overview

This dataset contains cleaned and structured sales data intended for data analysis, visualization, and machine-learning tasks. The file has been pre-processed to remove duplicates, handle missing values, and apply consistent formatting across all fields.

Rows: 5,000 (100% retained)
Columns: 20 (increased from 11)
Data Quality: 100% complete - no missing values, no duplicates, no errors
Coverage: 7 regions, 185 countries, 12 product types

---

📑 Column Description
| Column Name           | Description                         |
| --------------------- | ----------------------------------- |
| *Example:* `Order_ID` | Unique ID for each order            |
| `Product`             | Name of the product sold            |
| `Quantity`            | Number of units sold                |
| `Price`               | Selling price per unit              |
| `Total_Amount`        | Final amount (Quantity × Price)     |
| `Order_Date`          | Date of the transaction             |
| `Customer_Name`       | Name of the customer (if available) |
| `Region`              | Sales region/location               |


---

🧹 Data Cleaning Performed**
* Removed duplicate records
* Fixed inconsistent formatting
* Filled or removed missing values
* Converted date format to standard (YYYY-MM-DD)
* Calculated new fields where required (e.g., `Total_Amount`)
* Standardized text fields (case, spacing, categories)

---
🎯 Purpose of the Dataset

This cleaned dataset can be used for:
* Sales trend analysis
* Revenue forecasting
* Dashboard creation (Power BI, Tableau, Excel)
* Customer behavior analysis
* Machine learning models (prediction/classification)

---

📊 Recommended Analysis
* Monthly and yearly sales trends
* Top-selling products
* Profit and revenue analysis
* Region-wise sales performance
* Customer purchase patterns

---

Tools You Can Use

Python (Pandas, NumPy, Matplotlib)
Excel
