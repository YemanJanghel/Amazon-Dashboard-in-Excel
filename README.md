<img width="1366" height="589" alt="Image" src="https://github.com/user-attachments/assets/0126bcab-7694-4a4d-a571-16df9cf55ca6" />

📘 README — Sales Data Analytics Project


📂 File Overview
This Excel file consists of three sheets:

Sales Data – Raw transactional sales data.

KPI and Pivot – Key Performance Indicators and pre-generated pivot insights.

Dashboard 2 – Empty sheet intended for visualization/dashboard layout.

📄 1. Sheet: Sales Data
🔍 Purpose:
This is the core dataset containing individual sales transactions.

📌 Key Columns Explained:
Column Name	Description
Date	The date the sale occurred (YYYY-MM-DD format)
Sales Representative	Name of the person responsible for the sale
Product	Name of the product sold
Units	Number of product units sold
Price	Price per unit of the product
Total Sales	Units * Price — total revenue from the sale
City, State	Geographic location of the sale
Region	Region classification (North, South, East, West)
Days	Day of the week when the sale occurred (e.g., Monday, Friday)

📊 Sample Data:
mathematica
Copy
Edit
| Date       | Sales Rep        | Product                    | Units | Price | Total Sales | City     | State         | Region | Day    |
|------------|------------------|----------------------------|--------|-------|--------------|----------|----------------|--------|--------|
| 2013-01-11 | Christy Olson    | Nestle Toffee Crumble      | 1     | 100   | 100          | Surat    | Gujarat        | West   | Friday |
📄 2. Sheet: KPI and Pivot
🔍 Purpose:
This sheet contains key performance indicators and pivot tables summarizing insights.

🧮 Key Metrics Found:
Metric	Value
Achieved Sales	₹10,226,625
Target Sales	₹12,578,748.75
Most Sold Product	Nestle Smarties Pop-Up
Most Sales City	Trivandrum
Highest Avg. Price Item	Nestle Fab (₹303.84)

📌 Pivot Insights:
City-wise Total Sales

Product-wise Average Price

High-performing products and salespersons

You can turn these into KPI cards and Bar/Column charts in your dashboard.

📄 3. Sheet: Dashboard 2
Currently empty, can be used to design your dashboard using visuals like:

KPIs (cards)

Bar chart for top-selling products

Pie chart for region-wise sales

Line chart for sales over time

Map chart for sales by city/state (Power BI/Tableau)

📷 Suggested Dashboard Layout (Take Screenshots as Needed)
You can build your visuals in Excel/Power BI/Tableau and match with these descriptions:

Visual Type	Description	Data Source	Screenshot
KPI Cards	Achieved vs Target Sales, Most Sold Product	KPI and Pivot	📸 Place KPI cards on top
Bar Chart	Top 5 Products by Sales	Sales Data	📸 Show product names on X-axis
Pie Chart	Sales by Region	Sales Data	📸 Each slice = 1 region
Map Chart	Sales by City	Sales Data	📸 Location-based heatmap
Line Chart	Monthly Sales Trend	Sales Data	📸 Date on X-axis, sales on Y
