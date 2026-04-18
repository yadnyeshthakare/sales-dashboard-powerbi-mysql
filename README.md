# End-to-End Sales Data Pipeline & Analytics (MySQL → Power BI)

This project demonstrates the design and implementation of a data workflow that transforms raw transactional data into structured analytical datasets and interactive dashboards. It covers data modeling (star schema), data transformation, and visualization to support data-driven decision-making.

---

## Project Overview

**Tools Used:** MySQL, Power BI  
**Project Type:** Data Analytics (BI Pipeline)

The dataset was provided as a SQL dump file and imported into MySQL. The data was then explored, structured, and transformed before being connected to Power BI for building interactive dashboards.

---

## Dashboard Preview

![Sales Dashboard Preview](screenshots/sales_dashboard_preview.png)

---

## Workflow

1. Imported raw transactional data into MySQL.  
2. Explored and validated data using SQL (joins, aggregations).  
3. Designed a star schema data model (fact and dimension tables).  
4. Performed data cleaning and transformation using Power Query.  
5. Connected MySQL to Power BI for reporting.  
6. Built interactive dashboards for analysis.  

---

## Data Modeling

- Designed a star schema with fact and dimension tables
- Structured data to support efficient analytical queries and reporting
- Enabled slicing of data across time, products, customers, and markets

---

## Dashboard Features

- KPI tracking: ~₹986M revenue, ~2M sales quantity
- Revenue distribution by market/region
- Top customers by revenue contribution
- Product-level performance analysis
- Monthly and yearly sales trends
- Interactive filters (year and month slicers)

---

## Skills Demonstrated

- SQL for data extraction, joins, and aggregations
- Star schema design (fact & dimension tables)
- Data transformation using Power Query
- KPI dashboard development in Power BI
- Connecting relational databases to BI tools

---

## Business Impact

- Enabled visibility into ~986M total revenue and ~2M sales records  
- Identified high-performing products, customers, and markets  
- Supported data-driven decision-making through interactive dashboards  
- Improved understanding of sales trends and performance patterns  

---

## Repository Structure

- `data/` → SQL dump file (sales_database_dump.sql)  
- `dashboard/` → Power BI dashboard file (sales_dashboard.pbix)  
- `screenshots/` → Dashboard preview images  
- `README.md` → Project documentation  

---

## How to Run

1. Create or open a MySQL database and import the SQL dump file  
2. Open the Power BI (.pbix) file  
3. Update database connection details if required  
4. Refresh the data to load it from MySQL  
5. Explore the interactive dashboard  

---

## Example Use Cases

- Monitoring overall sales performance  
- Identifying high-value customers and key markets  
- Tracking revenue trends over time  
- Analyzing product contribution to revenue  

---

## Author

**Yadnyesh Thakare**  
LinkedIn: https://linkedin.com/in/yadnyesh-thakare/  
Email: thakareyadnyesh@gmail.com  

---

## Summary

This project demonstrates a practical implementation of a data pipeline and analytics workflow, converting raw database records into structured insights and business dashboards. It reflects real-world reporting and data processing tasks commonly used in analytics and data engineering roles.
