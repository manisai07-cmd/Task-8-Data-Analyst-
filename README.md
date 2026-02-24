# Task-8-Data-Analyst-
This project focuses on designing an interactive Sales Performance Dashboard to analyze business performance across time, regions, and product categories.

The dashboard provides a clear visual representation of key sales metrics to support business decision-making and performance evaluation.

The solution was developed using Microsoft Power BI Desktop.

🎯 Objective

To build a clean, interactive, and business-friendly dashboard that:

Analyzes monthly sales trends

Compares regional sales performance

Evaluates product category contribution

Enables dynamic filtering using slicers

Extracts meaningful business insights

🛠 Tools & Technologies

Microsoft Power BI Desktop

DAX (Data Analysis Expressions)

CSV Dataset (Superstore Sales Data)

📁 Dataset Description

The dataset includes transactional sales records with the following key fields:

Order Date

Region

Category

Sales

Profit

Customer Name

Segment

Market

The data was validated for correct data types and consistency before building the dashboard.

🔄 Data Preparation & Transformation

The following preprocessing steps were performed:

Imported CSV dataset into Power BI.

Verified and corrected data types:

Order Date → Date

Sales & Profit → Decimal Number

Created a calculated column to analyze monthly trends:

MonthYear = FORMAT([order_date], "MMM YYYY")

Sorted Month-Year chronologically using Order Date.

Ensured no null or inconsistent values impacted visuals.

📊 Dashboard Components

The dashboard includes the following visuals:

1️⃣ Line Chart – Sales Trend Over Time

Displays monthly sales performance to identify trends and seasonality.

2️⃣ Bar Chart – Sales by Region

Compares total sales across different regions.

3️⃣ Donut Chart – Sales by Category

Shows proportional contribution of each product category.

4️⃣ KPI Card – Total Sales

Highlights overall revenue performance.

5️⃣ Slicer – Region / Category

Enables interactive filtering for dynamic analysis.
