# Retail Sales & Returns Analysis

## 🎯 Business Context
The goal of this project is to analyze the impact of product returns on overall profitability. By identifying whether return patterns are linked to specific products or specific time periods (seasonal trends), the business can take corrective actions to reduce losses and improve customer satisfaction.

## 📊 KPIs & DAX
I developed the following key metrics to monitor performance and return impact:
* **Total Sales**: Gross revenue before returns.
* **Total Returns**: Total number of returned items.
* **Return Rate**: Percentage of sales that resulted in a return (Crucial for identifying quality issues).
* **Total Profit**: Net profit after accounting for the cost of returns.
* **Profit Margin %**: The efficiency of the sales in generating profit.

## 🛠️ Data Cleaning & Modeling
The dataset required specific transformations to allow for deep time-series analysis:
* **Time Intelligence**: Split Date and Time columns to analyze return peaks by hour of day and day of week.
* **Data Relationship**: Established a robust link between the Sales table and the Returns table using unique Transaction IDs.
* **Calendar Table**: Created a custom DAX Calendar table to enable Year-over-Year (YoY) and Month-over-Month (MoM) comparisons.
* **Format Standardization**: Cleaned currency formats and handled null values in return reason columns.

## 🚀 Tools Used
* **Power BI** (DAX, Power Query)
* **CSV** (Initial Data Source)
