# Supply Chain & Operations Analytics

## Overview

This project analyzes supply chain and operations data using Python to understand
sales, delivery performance, supplier performance, inventory, and regional trends.

The analysis focuses on cleaning raw data, exploring patterns, calculating useful
business metrics, and identifying areas that may need attention.

## Business Questions

- Which product categories generate the most revenue?
- Which products have the highest revenue?
- Which regions generate the most revenue?
- Which suppliers have longer delivery times?
- What percentage of orders are delayed?
- Which products have low inventory?
- How does revenue change over time?
- Which areas show potential operational issues?

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset

The project uses supply chain data containing information about:

- Orders
- Products
- Suppliers
- Inventory
- Regions
- Delivery status
- Revenue and costs

The data is divided into separate files and connected using common IDs such as
`product_id` and `supplier_id`.

## Analysis Performed

### Data Cleaning
- Checked for missing values
- Checked for duplicate records
- Converted date columns into the correct format
- Reviewed data types
- Created calculated fields for analysis

### Exploratory Data Analysis

The analysis covers:

- Revenue by category
- Revenue by region
- Top products by revenue
- Delivery status
- Average delivery time by supplier
- Monthly revenue trends
- Inventory patterns

## Key Metrics

The project calculates metrics such as:

- Total Revenue
- Total Orders
- Average Delivery Days
- Delay Days
- Profit Margin
- Delayed Orders
- Inventory Status

## Visual Analysis

Python charts are used to understand:

- Monthly revenue trends
- Revenue by category
- Revenue by region
- Orders by delivery status
- Supplier delivery performance

## Business Insights

The analysis is used to identify:

- High-performing product categories
- High-revenue products
- Regional performance differences
- Supplier delivery performance
- Delivery and operational issues
- Inventory areas that may require attention

## Project Structure

Supply-Chain-Operations-Analytics/

├── Supply_Chain_Operations_Analytics.ipynb

├── data/

│   ├── orders.csv

│   ├── products.csv

│   ├── suppliers.csv

│   └── inventory.csv

└── README.md

## Future Work

- Perform SQL-based analysis
- Add additional business metrics
- Expand the analysis with more operational insights