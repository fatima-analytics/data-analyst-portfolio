# Technical Insights & Analysis Logic — Excel Sales

## 🧠 Analysis Methodology
This project demonstrates the use of **Power Query** for ETL in Excel. The logic was to create a "Star Schema" within Excel by linking a flat sales table to a dynamic Calendar table created with formulas.

## 🛠️ Tools & Functions Used
* **XLOOKUP**: Used to fetch product prices and customer tiers from secondary sheets.
* **Pivot Calculations**: Used "Show Values As % of Grand Total" to analyze market share per product.
* **Data Validation**: Applied to the "Input" sheet to ensure no incorrect dates or negative quantities are entered.

## 📈 Key Findings
* **Customer Concentration**: 20% of customers generate 80% of the total revenue (Pareto Principle).
* **Inventory Turnover**: Certain products have high "Median Quantities" but low "Order Counts," indicating bulk buying patterns.

## 💡 Operational Recommendations
* **Loyalty Program**: Target the top 10% of customers identified in the "Customer Performance" slicer with exclusive discounts.
* **Stock Optimization**: Increase safety stock for products identified as "Top Sellers" to avoid stockouts during peak months.
