Procurement Spend Analysis

End-to-End Data Analytics Project

📌 Project Overview

This project analyzes organizational procurement data to identify spending patterns, supplier dependency, pricing inefficiencies, and cost optimization opportunities.
An end-to-end analytics pipeline was implemented using Python, PostgreSQL, and Power BI to transform raw transactional data into actionable business insights.

🎯 Business Problem

Organizations often lack visibility into procurement spend, leading to:

Supplier dependency risks

Price inconsistencies

Poor cost governance

This project addresses these challenges by applying structured data analytics and visualization techniques.

🧾 Dataset Overview

Total Records: 500

Total Columns: 9

Key Attributes

Transaction Details: Transaction ID, Item Name, Category

Cost Metrics: Quantity, Unit Price, Total Cost

Procurement Context: Supplier, Buyer, Purchase Date

🧹 Data Quality & Preparation (Python)
Tools Used

Pandas

NumPy

Matplotlib / Seaborn

Key Steps

Validated data types and formats

Converted purchase dates to datetime format

Verified numerical consistency

Performed exploratory data analysis

Key EDA Insights

Spend distribution is right-skewed

Software and furniture dominate total spend

Buyer spending behavior varies significantly

📌 Notebook: notebooks/spend_analysis_eda.ipynb

🗄️ Database & SQL Analysis (PostgreSQL)

The cleaned dataset was loaded into PostgreSQL for structured querying and business analysis.

Business Questions Answered

Total procurement exposure

Supplier spend & dependency

High-risk / high-value transactions

Monthly spend trends

Item & category dominance

Price variance and inefficiencies

Supplier efficiency benchmarking

Potential cost savings estimation

📌 SQL Queries: sql/spend_analysis_queries.sql

📈 Power BI Dashboard
Dashboard Highlights

Total Spend & Avg Transaction Value

Category & Supplier Spend Distribution

Monthly Spend Trends

Supplier Efficiency Indicators

📌 File: powerbi/procurement_spend_dashboard.pbix

💡 Key Business Insights

A small number of high-value transactions drive most of the spend

Supplier dependency introduces operational risk

Significant price inconsistencies exist across purchases

Clear opportunities for cost optimization were identified

✅ Business Recommendations

Introduce approval thresholds for high-value purchases

Reduce supplier dependency through diversification

Standardize pricing benchmarks

Monitor supplier efficiency regularly

🏁 Conclusion

This project demonstrates a complete procurement analytics workflow using Python, SQL, and Power BI.
It showcases practical data engineering, analytics, and business intelligence skills suitable for real-world decision-making.

🔮 Future Enhancements

Predictive spend forecasting

Supplier performance scoring models

Automated anomaly detection

Real-time BI dashboards

🛠️ Tools & Technologies

Python (Pandas, NumPy)

PostgreSQL

Power BI

📎 Author

Abhijith S
Aspiring Data Analyst | Business Analyst
