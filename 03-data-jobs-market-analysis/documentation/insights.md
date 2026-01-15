# Technical Insights & Analysis Logic — Data Job Market

## 🧠 Analysis Methodology
The main technical task was **Salary Normalization**. I had to convert `Hourly Rate` into `Yearly Salary` (using a standard 2,080 hours/year logic) to allow for a "Median Salary" comparison across different job types.

## 🛠️ Data Dictionary & Calculations
* **Adjusted Median Salary**: Uses the `MEDIAN()` function instead of `AVERAGE()` to prevent extreme executive salaries from skewing the results.
* **Rating vs Salary**: Correlation analysis between `Company Rating` (1-5 stars) and the salary offered.
* **Year-over-Year (YoY) Growth**: Tracking how the number of "Data Analyst" postings changed compared to the previous year.

## 📈 Key Findings
* **Location Premium**: Remote roles offer 12% higher median salaries than on-site roles in certain regions.
* **Skill Value**: Job descriptions mentioning "Cloud" or "Advanced DAX" carry a 15% salary premium.

## 💡 Career Recommendations
* **Skill Focus**: Aspiring analysts should prioritize Power BI and SQL.
