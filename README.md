
# Online Retail Sales Analysis and Excel Dashboard

## Project Overview

This project analyzes an online retail transaction dataset using Microsoft Excel. The goal is to transform raw transaction data into meaningful business insights through data cleaning, analysis, customer segmentation, and visualization.

The project follows a practical data analysis workflow:

**Raw Data → Data Cleaning → Data Analysis → Visualization → Business Insights**

## Project Objectives

- Inspect and assess data quality.
- Clean and prepare transaction data for analysis.
- Analyze sales performance, products, and countries.
- Segment customers using RFM analysis.
- Build an interactive Excel dashboard.
- Develop business insights and recommendations.

## Tools and Techniques

- **Microsoft Excel 2010**
- Excel formulas: IF, SUMIFS, COUNTIFS, IFERROR, and XLOOKUP
- Data cleaning and quality auditing
- Duplicate detection
- PivotTables and Pivot Charts
- KPI development
- RFM customer segmentation
- Dashboard design and data visualization

## Data Preparation

The original dataset contains 541,909 transaction records.

Data preparation included:

- Checking missing values.
- Identifying duplicate records.
- Reviewing cancelled transactions.
- Identifying invalid quantities and unit prices.
- Separating eligible sales transactions from records requiring review.
- Preparing cleaned sales data for analysis.

The original data was preserved separately from the cleaned analysis data.

## Key Performance Indicators

| KPI                  |         Result |
| -------------------- | -------------: |
| Total Revenue        | £10,642,110.80 |
| Total Quantity Sold  |      5,572,420 |
| Identified Customers |          4,338 |
| Top Product Revenue  |    £174,156.54 |

**Note:** Overall sales revenue includes eligible transactions without a Customer ID. RFM segmentation covers only the 4,338 identified customers, so the two revenue populations are different.

## Dashboard

The Excel dashboard presents:

- Four key performance indicators.
- Customer segment distribution.
- Top 10 countries by revenue.
- Top 10 products by revenue.
- Monthly revenue trend.

## Key Business Insights

- Best Customers contribute the largest share of identified-customer revenue.
- REGENCY CAKESTAND 3 TIER is the highest-revenue normal merchandise product.
- The United Kingdom is the leading market by revenue.
- Customer segmentation helps identify valuable customers and those who may need re-engagement.

## Business Recommendations

- Develop retention strategies for valuable customers.
- Maintain sufficient stock of high-performing products.
- Strengthen the leading market while exploring growth opportunities in other countries.
- Use customer segmentation to support targeted marketing campaigns.

## Project Files

- `Online_Retail_Sales_Analysis_Portfolio.xlsb` — Excel analysis workbook and dashboard.
- `dashboard.png` — Dashboard screenshot.
- `README.md` — Project documentation.

## Conclusion

This project demonstrates a complete Excel-based data analysis workflow, from data quality assessment and cleaning to business analysis, visualization, and recommendations.
