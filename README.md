Vrinda Store Sales Analysis Dashboard
An interactive retail sales analysis dashboard built in Microsoft Excel using PivotTables, PivotCharts, and slicers. The workbook explores order trends, sales performance, customer demographics, order status, sales channels, and geographic performance.
Repository
Suggested repository name: vrinda-store-sales-analysis

Short description:
Interactive retail sales dashboard built with Microsoft Excel, PivotTables, PivotCharts, and slicers to explore sales, orders, customer demographics, channels, and state-wise performance.
Project Overview
This project uses a retail order dataset containing 31,047 transaction-level rows and 21 columns. The workbook includes the source data and a separate report sheet containing a consolidated dashboard.

The dashboard is designed to help a user explore questions such as:
- How do order volume and sales amount change month by month?
- Which states contribute the most to sales?
- How do orders vary across age groups and gender?
- Which sales channels contribute to orders?
- What is the distribution of order statuses?
- How does total sales compare between men and women?
Tools and Excel Features
- Microsoft Excel
- Excel Tables
- PivotTables
- PivotCharts
- Slicers
- Data summarization and visual analysis
Dataset Structure
The source data includes fields such as:
Field	Description
Order ID	Order identifier
Cust ID	Customer identifier
Gender	Customer gender
Age	Customer age
Age Group	Customer age segment
Date / Month	Order date and month
Status	Order status
Channel	Sales channel
SKU	Product identifier
Category	Product category
Size	Product size
Qty	Quantity ordered
Amount	Order amount
Ship-city / Ship-state	Shipping location
B2B	Business-to-business indicator


The workbook also contains supporting fields such as an index, currency, and shipping postal/country information.
What Was Built
The Vrinda Store Report sheet brings together six main visual analyses:
1. Orders vs Sales — compares monthly order counts with sales amount using a combination chart.
2. Top 10 States — ranks states by sales amount.
3. Orders: Age vs Gender — compares order distribution across age groups and gender.
4. Orders: Channels — shows the contribution of different sales channels to orders.
5. Order Status — visualizes the distribution of order outcomes, including delivered, cancelled, returned, and refunded orders.
6. Sales Total (Men vs Women) — compares the share of sales amount by gender.
Interactive Dashboard
Three slicers are included to filter the PivotTable-based report:
- Category — filter results by product category.
- Channel — filter results by sales channel.
- Month — filter results by month.
The slicers are connected to the dashboard's PivotTables so that supported charts update when filters are selected. Use the original .xlsx workbook in desktop Microsoft Excel for the intended slicer experience. Some spreadsheet viewers and conversions to Google Sheets may not preserve Excel slicer functionality.
How to Use
1. Download Vrinda Store Data Analysis.xlsx from this repository.
2. Open the workbook in desktop Microsoft Excel.
3. Navigate to the Vrinda Store Report sheet.
4. Use the Category, Channel, and Month slicers to filter the report.
5. Review the charts to compare sales and order patterns.
For the full interactive experience, use Microsoft Excel. A static preview or converted spreadsheet may not retain all Excel-specific interactions.

Repository Contents
vrinda-store-sales-analysis/
├── Vrinda Store Data Analysis.xlsx
├── README.md
└── images/
    └── dashboard-preview.png
Add a screenshot of the dashboard as images/dashboard-preview.png if you want the dashboard preview to appear on the GitHub repository page. The screenshot is optional; the Excel workbook is the main project file.
Skills Demonstrated
- Organizing and working with structured tabular data
- Building PivotTables to summarize transaction data
- Creating PivotCharts to communicate sales and order patterns
- Comparing customer segments and sales channels
- Using slicers to make an Excel report interactive
- Presenting multiple business views in a consolidated dashboard
Notes and Limitations
- The analysis and dashboard descriptions above are based on the workbook's visible sheets, fields, PivotTables, charts, and slicer definitions.
- This repository describes the analysis included in the workbook; it does not claim a separate statistical model, forecasting process, SQL workflow, or automated data-cleaning pipeline.
- The dashboard is intended to be explored in desktop Microsoft Excel. Compatibility can vary in browser-based spreadsheet viewers.
Author
Lokesh Kumawat
