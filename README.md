# E-commerce-customer-churn-analysis-using-sql
SQL-based E-Commerce Customer Churn Analysis project focused on data cleaning, transformation, and extracting business insights. Includes KPI analysis, customer segmentation, and churn behavior using advanced SQL queries, aggregations, and joins.

This project focuses on analyzing customer behavior and churn patterns using SQL on an e-commerce dataset. The objective is to clean, transform, and analyze the data to extract meaningful business insights that can help improve customer retention and decision-making.

## Key Tasks Performed

* Data cleaning and preprocessing:

  * Handled missing values using mode imputation
  * Removed outliers for better data accuracy
  * Standardized inconsistent categorical values
  * Renamed columns for better readability

* Feature engineering:

  * Created new columns such as `ChurnStatus` and `ComplaintReceived`
  * Categorized customers based on warehouse-to-home distance

* Data analysis using SQL:

  * Calculated churn distribution and key KPIs
  * Analyzed customer behavior based on tenure, cashback, and complaints
  * Identified high-value customer segments
  * Evaluated preferred payment modes and order categories
  * Performed aggregation, filtering, and subquery-based analysis

* Advanced SQL operations:

  * Used `GROUP BY`, `HAVING`, `CASE`, and subqueries
  * Created and joined an additional table (`customer_returns`)
  * Performed JOIN operations to analyze return behavior of churned customers

##  Key Insights

* Customers with higher complaints show a higher likelihood of churn
* Distance from warehouse impacts customer retention
* Certain categories and payment modes contribute more to revenue
* High-value customers can be identified based on order frequency and tenure

## Tools Used

* SQL (MySQL)
* Data Cleaning & Transformation Techniques
* Analytical Querying

##  Conclusion

This project demonstrates how SQL can be effectively used to clean, transform, and analyze real-world data to derive actionable insights. It highlights the importance of data-driven decision-making in improving customer retention and business performance.

