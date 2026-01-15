# Technical Insights & Analysis Logic — Retail & Returns

## 🧠 Analysis Methodology
The challenge was to link the `Sales` table with the `Returns` table. The focus is on the "Net Profit," which is the revenue remaining after subtracting the costs of returned goods and restocking fees.

## 🛠️ Data Dictionary & Calculations
* **Return Rate**: `COUNT(Returns[TransactionID]) / COUNT(Sales[TransactionID])`.
* **Net Profit**: `SUM(Sales[Profit]) - SUM(Returns[Loss])`.
* **Return Velocity**: Analysis of how many days pass between the purchase and the return.

## 📈 Key Findings
* **Product Quality**: Three specific product categories represent 60% of all returns, suggesting potential quality issues or misleading descriptions.
* **Seasonality**: Return rates spike 20% in January, likely due to post-holiday gift returns.

## 💡 Business Recommendations
* **Product Description Update**: Improve website descriptions for high-return items to better manage customer expectations.
* **Return Policy**: Implement a tiered return window to encourage faster returns of seasonal items.
