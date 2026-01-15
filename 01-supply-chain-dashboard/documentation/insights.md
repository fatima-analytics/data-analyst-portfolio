# Technical Insights & Analysis Logic — Supply Chain

## 🧠 Analysis Methodology
The core of this analysis focuses on the "Lead Time" (the difference between `Order Date` and `Shipping Date`). From a logistics perspective, reducing this gap is key to customer satisfaction and inventory turnover.

## 🛠️ Data Dictionary & Calculations
* **Lead Time**: `DATEDIFF('Order Date', 'Shipping Date', DAY)`. This measure identifies bottlenecks in the warehouse processing phase.
* **Late Delivery Rate**: Calculated by comparing `Actual Shipping Date` vs `Scheduled Shipping Date`.
* **Profit per Item**: `Total Profit / Quantity`. This helps identify which products are costly to ship compared to their margin.

## 📈 Key Findings
* **Bottleneck Identification**: Analysis showed that 15% of delays occur during weekend orders, suggesting a need for staff adjustment.
* **Fraud Detection**: High correlation found between specific shipping regions and "Suspected Fraud" flags.

## 💡 Logistics Recommendations
* **Process Automation**: Automate label generation for high-volume items to reduce manual lead time by an estimated 10%.
* **Carrier Review**: Re-evaluate contracts with carriers showing a late delivery rate above 5%.
