# Data Jobs Market Analysis

## 🎯 Business Context
The objective of this analysis is to identify the highest-paying roles in the data industry and determine which geographical locations offer the best compensation. This project also tracks job posting trends and company ratings to help professionals make data-driven career decisions.

## 📊 KPIs & DAX
I developed several measures to standardize salary data and rank job opportunities:
* **Median Yearly Salary**: The midpoint salary to avoid distortion from extreme outliers.
* **Salary Star Rating**: A custom rating system based on compensation levels vs. industry averages.
* **Job Posting Pulse**: Tracking the volume of jobs over time based on the "Job Posted Date."
* **Role Popularity**: Count of job openings per specific data title (Analyst, Scientist, Engineer).

## 🛠️ Data Cleaning & Engineering
This project involved significant data preparation to ensure salary consistency:
* **Salary Normalization**: Created a logic to convert hourly wages into estimated yearly salaries for easier comparison.
* **Outlier Removal**: Filtered out unrealistic salary entries that would skew the median.
* **Company Rating Cleanup**: Standardized rating scales and handled missing values for new companies.
* **Geographical Mapping**: Grouped locations into regions to analyze global salary trends.
* **Date Dimension**: Extracted Year and Month from posting dates to visualize hiring seasonality.

## 🚀 Tools Used
* **Power BI** (Power Query & DAX)
* **CSV** (Raw dataset)
