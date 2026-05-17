E-Commerce Sales & Customer Analytics

Using SQL, Python, and Power BI

Project Overview

This project analyzes e-commerce sales performance, customer behavior, delivery efficiency, and product trends using the Brazilian Olist E-Commerce Dataset.

The project combines SQL, Python, and Power BI to generate business insights and build an interactive analytics dashboard for KPI monitoring and decision-making.

Key analysis areas include:

Sales performance
Customer analytics
Order trends
Product category performance
Regional sales analysis
Delivery efficiency
Customer satisfaction
Business KPI tracking
Dataset

Dataset Used:

Olist E-Commerce Dataset

Main tables used in the analysis:

Table	Description
customers	Customer information
orders	Order details and timestamps
order_items	Products purchased
products	Product metadata
payments	Payment information
reviews	Customer reviews
sellers	Seller information
Tools & Technologies
Python
Pandas
SQLite
SQL
Matplotlib
Seaborn
Power BI
Jupyter Notebook
Business Questions

This project answers the following business questions:

What are the overall sales trends?
Which product categories generate the most revenue?
Which customers spend the most?
What is the repeat customer rate?
Which regions generate the highest sales?
How efficient are deliveries?
Which sellers perform best?
What factors impact customer satisfaction?
SQL Techniques Used

The project demonstrates multiple SQL concepts including:

JOINs
GROUP BY analysis
Aggregate functions
Common Table Expressions (CTEs)
CASE WHEN statements
Window functions
Revenue trend analysis
Customer segmentation
KPI calculations
Key Analysis Performed
Sales Analysis
Total revenue calculation
Monthly revenue trend analysis
Revenue running totals
Average order value analysis
Product Analysis
Top-performing product categories
Revenue contribution by category
Customer Analysis
Top customers by spending
Repeat customer analysis
Customer segmentation using CASE WHEN
Regional Analysis
Revenue analysis by state
Regional sales performance comparison
Seller Analysis
Top sellers by sales value
Seller order performance
Operations Analysis
Order status distribution
Delivery performance analysis
Average delivery time calculation
Key Business Insights
Revenue demonstrated strong growth throughout 2017 with noticeable seasonal purchasing trends.
Bed, Bath & Table, Health & Beauty, and Computer Accessories were the top-performing product categories by revenue.
Most customers placed only one order, highlighting opportunities to improve customer retention.
Repeat customers contributed significantly to long-term revenue generation.
São Paulo (SP) generated the highest marketplace revenue among all states.
Average order value was approximately 161 BRL per transaction.
Average delivery time for completed orders was approximately 12.6 days.
A relatively small group of sellers contributed disproportionately to total marketplace sales.
Business Recommendations
Improve customer retention through loyalty and repeat-purchase campaigns
Focus marketing efforts on high-performing product categories
Optimize delivery operations to reduce shipping times
Strengthen partnerships with top-performing sellers
Power BI Dashboard

An interactive Power BI dashboard was developed to visualize:

Revenue trends
Customer behavior
Product category performance
Regional sales analysis
Order status distribution
Business KPIs
Dashboard Features
Interactive filtering
KPI cards
Revenue trend analysis
Customer insights
Regional sales visualization
Product category analysis

Note: The Power BI .pbix file exceeded GitHub upload limits. Dashboard screenshots and exports are included in the repository.

Repository Structure
├── notebooks/
│   └── ecommerce_sales_analysis.ipynb
│
├── images/
│   ├── dashboard_overview.png
│   ├── sales_analysis.png
│   └── customer_analysis.png
│
├── dashboard/
│   └── dashboard_export.pdf
│
├── README.md
└── requirements.txt
Project Deliverables
SQL business analysis queries
Python data analysis workflow
Power BI dashboard
Business insights and recommendations
Data visualizations
Future Improvements

Potential future enhancements include:

Customer churn prediction modeling
RFM customer segmentation
Forecasting sales trends
Advanced Power BI DAX measures
Interactive dashboard deployment
Author
Kulwinder Bhamra
Created as part of a data analytics portfolio project demonstrating SQL, Python, and Power BI skills.
