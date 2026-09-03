# 📊 Power BI Superstore Sales Analysis & Interactive Dashboard

## 📌 Project Overview

This project demonstrates the use of Microsoft Power BI for Business Intelligence and Data Analytics.

The project uses a Superstore sales dataset to perform the complete data analytics workflow:

Data Import → Data Cleaning → Data Modeling → DAX → Visualization → Interactive Dashboard → Business Insights

The main objective is to analyze sales and profitability and create an interactive dashboard that supports data-driven business decisions.

---

## 🎯 Objectives

The main objectives of this project are:

- Import and inspect business data in Power BI
- Clean and prepare data using Power Query
- Create relationships between multiple tables
- Develop DAX measures for business calculations
- Create meaningful data visualizations
- Build an interactive dashboard
- Analyze business performance
- Identify important trends and patterns
- Provide data-driven business recommendations

---

## 📂 Dataset

The project uses a Superstore sales dataset containing three tables:

### 1. Orders

The main table used for sales analysis.

Important columns include:

- Order ID
- Order Date
- Ship Date
- Customer Name
- Segment
- Country
- City
- State
- Region
- Product Name
- Category
- Sub-Category
- Sales
- Quantity
- Discount
- Profit

### 2. People

Contains regional information.

Columns:

- Person
- Region

### 3. Returns

Contains information about returned orders.

Columns:

- Returned
- Order ID

---

# 🛠️ Tools & Technologies

- Microsoft Power BI Desktop
- Power Query
- DAX
- Excel
- Data Visualization
- Business Intelligence

---

# 📋 Project Tasks

## Task 1 — Power BI Introduction & Data Import

The Power BI interface was explored and the Orders dataset was imported.

The available columns and their data types were inspected.

The purpose of Power BI in Business Intelligence and Data Analytics was also studied.

---

## Task 2 — Data Cleaning & Preparation

Power Query was used to inspect and prepare the dataset.

The following activities were performed:

- Checked missing values
- Checked duplicate records
- Verified data types
- Renamed columns where required
- Removed unnecessary columns where applicable
- Applied suitable transformations

The cleaned dataset was prepared for analysis.

---

## Task 3 — Data Modeling & Relationships

Multiple tables were used to create a basic Power BI data model.

Tables used:

- Orders
- People
- Returns

Relationships were created using relevant common fields such as Order ID and regional information.

This allowed related data from multiple tables to be analyzed together.

---

## Task 4 — DAX Measures

Several DAX measures were created to calculate important business metrics.

### Total Sales

```DAX
Total Sales = SUM('Orders'[Sales])
Total Profit
Total Profit = SUM('Orders'[Profit])
Average Sales
Average Sales = AVERAGE('Orders'[Sales])
Total Records
Total Records = COUNTROWS('Orders')
Maximum Sales
Maximum Sales = MAX('Orders'[Sales])
Minimum Sales
Minimum Sales = MIN('Orders'[Sales])
Profit Margin
Profit Margin % = DIVIDE([Total Profit], [Total Sales], 0)

These measures were used in cards and other visualizations.

📊 Task 5 — Power BI Visualizations

The following visualizations were created:

Sales by Category

A column chart was used to compare sales between product categories.

Sales Trend Over Time

A line chart was used to analyze sales trends across different years.

Sales by Segment

A donut chart was used to show the contribution of different customer segments.

Category Performance

A table was created to display category and sub-category performance using sales, profit, and record count.

Total Sales

A Card visual was used to display the overall sales value.

📈 Task 6 — Interactive Dashboard

An interactive dashboard named:

SUPERSTORE SALES PERFORMANCE DASHBOARD

was created.

KPI Cards

The dashboard contains:

Total Sales
Total Profit
Profit Margin %
Visualizations

The dashboard includes:

Sales by Category
Total Sales by Year
Total Sales by Segment
Category Performance
Interactive Filters

Two slicers were added:

Region
Category

The slicers allow users to interact with the dashboard and dynamically filter the displayed results.

🔍 Task 7 — Business Insights

The dashboard provided several important business insights.

Insight 1

Technology is one of the strongest-performing categories based on sales.

Insight 2

Office Supplies has comparatively lower sales than the other major categories.

Insight 3

Sales show an overall increasing trend from 2012 to 2015.

Insight 4

Consumer customers contribute the largest share of sales.

Insight 5

The business generated approximately 12.64M in total sales and 1.47M in total profit, resulting in an overall profit margin of approximately 12%.

💡 Business Recommendations
Recommendation 1

The company should focus on the Technology category and Consumer segment through targeted marketing, inventory planning, and customer-focused strategies.

Recommendation 2

The company should investigate low-profit sub-categories by reviewing pricing, discounts, product costs, and shipping expenses to improve profitability.

📊 Key Results
Metric	Result
Total Sales	12.64M
Total Profit	1.47M
Profit Margin	12%
Main Analysis Table	Orders
Number of Tables	3
Dashboard Slicers	2
KPI Cards	3
📁 Project Structure
PowerBI-Superstore-Sales-Analysis/
│
├── README.md
│
├── Dataset/
│   └── Superstore_Dataset.xlsx
│
├── PowerBI/
│   └── PowerBI_Assignment_Final.pbix
│
└── Screenshots/
    ├── Task01_Data_Import.png
    ├── Task02_Data_Cleaning.png
    ├── Task03_Data_Model.png
    ├── Task04_DAX.png
    ├── Task05_Visualizations.png
    ├── Task06_Dashboard.png
    └── Task07_Insights.png
🎯 Conclusion

This project demonstrates the practical use of Power BI for Business Intelligence and Data Analytics.

The project covers data import, data cleaning, data modeling, DAX calculations, visualization, interactive dashboard development, and business analysis.

The final dashboard provides a clear overview of sales and profitability and allows users to explore the data using interactive filters.

The insights generated from the dashboard can help businesses make better decisions related to sales, marketing, inventory, pricing, and profitability.

👩‍💻 Author

Vaishnavi

B.Tech Computer Science Engineering

