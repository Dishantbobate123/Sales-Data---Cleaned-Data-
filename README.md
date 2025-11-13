Sales Data - Cleaned Dataset for Power BI Dashboard
Overview
This repository contains the cleaned and processed sales dataset originally sourced as "Sales_Data.csv." The data has been thoroughly cleaned and enhanced for effective use in Power BI dashboard development.

Dataset Description
Rows: 5,000 sales records
Columns: 20 attributes including original and calculated fields
Data Period: 2010 to 2017
Geographic Coverage: 7 regions worldwide, 185 countries
Product Categories: 12 item types (Fruits, Beverages, Baby Food, etc.)

Data Cleaning Summary
Missing values in Item_Type filled with "Unknown"
Missing Order_ID values replaced with unique generated IDs
Dates (Order_Date, Ship_Date) standardized to ISO datetime format
Converted Order_ID to integer for consistency
Added new calculated columns to support advanced analysis:
  Total_Revenue
  Total_Cost
  Profit
  Profit_Margin_Percent
  Days_to_Ship
  Order_Year, Order_Month, Order_Quarter, Order_Month_Name

Usage
This dataset is optimized for import into Power BI for sales performance visualization, profitability analysis, and operational metrics tracking.
