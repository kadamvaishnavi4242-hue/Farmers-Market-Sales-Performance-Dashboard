# Farmers-Market-Sales-Performance-Dashboard
An interactive Power BI dashboard for Farmers Market data analysis, featuring sales trends, vendor performance, and quantity metrics.
##  Project Overview
This project features an interactive Power BI Dashboard designed to analyze a Farmers Market dataset. The dashboard provides a 360-degree view of sales performance, inventory movement, and vendor efficiency.
## Technical Steps (ETL Process)
I transformed 4 Raw (Dirty) Data files into an analysis-ready format using Power Query:
Data Cleaning: Removed nulls and standardized inconsistent records.
Data Typing: Converted Zip Codes to Text to enable categorical analysis.
Indexing: Applied custom indexing to maintain categorical order on the X-axis.
Calculations: Created measures for Total Sales, Quantity, and Vendor performance.
##  Key Analysis Performed
### 1. Sales-wise Analysis (Revenue Focus)
Total Revenue: Monitored the overall sales through the Total Sale ($4.42K) KPI card.
Financial Trends: Used date-based slicers to track how revenue changes over different market periods.
### 2. Quantity-wise Analysis (Inventory Volume)
Product Demand: Identified high-volume products using the Product vs. Quantity bar chart.
Vendor Distribution: Analyzed which vendors are moving the most stock using the Vendor vs. Quantity Donut Chart.
### 3. Sales & Quantity Combined (Performance Metrics)
Customer Behavior: Developed a detailed table to see exactly which customer are buying which products and in what quantity.
Geographical Trends: Created the New_zip vs. Quantity Area Chart to visualize demand distribution across different locations.
## Repository Structure
Raw_Data/: Contains the 4 original files (Dirty Data).
Cleaned_Data/: Contains the 4 processed files (Cleaned Data).
Farmers_Market_Project.pbix: The final interactive Power BI file.
Dashboard_Preview.jpg: A full-page screenshot of the final report.
## How to Interact with this Dashboard
Download the .pbix file.
Open it in Power BI Desktop.
Use the Slicers (Vendor, Market Date, Product) at the top to filter the entire dashboard.
