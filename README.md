# Coffee Shop Sales Analysis Using SQL

This project demonstrates the use of SQL for cleaning, transforming, and analyzing real-world sales data from a coffee shop. The dataset contains over **100,000 rows** of transactional data including sales date, time, quantity, product details, and location.
## Dataset Summary
The dataset includes the following fields:
- `transaction_id`
- `transaction_date`
- `transaction_time`
- `product_category`
- `product_type`
- `unit_price`
- `transaction_qty`
- `store_location`

## Key Tasks Performed

- Converted improperly formatted **date** and **time** columns
- Renamed incorrectly encoded columns
- Ensured correct **data types** for all columns
- Calculated key **KPIs**: total sales, total orders, total quantity sold
- Performed **month-over-month trend analysis**
- Conducted breakdowns by:
  - Date and day of the week
  - Hour of the day
  - Store location
  - Product category and type
- Compared **daily performance to average sales**
- Used **aggregate functions**, **window functions**, and **conditional logic** for advanced analysis

## Skills Demonstrated

- SQL data cleaning and preprocessing
- Use of `STR_TO_DATE`, `ALTER TABLE`, and `MODIFY COLUMN`
- KPI computation using `SUM()`, `COUNT()`, `AVG()`, and `ROUND()`
- Trend analysis using `LAG()` and `OVER()`
- Time-based and category-based performance evaluation
- Query optimization and structuring for reporting

## Purpose

This project showcases how SQL can be used to derive actionable business insights from raw sales data. It reflects real-world scenarios where data preprocessing and meaningful metric generation are essential for business intelligence and reporting.


Feel free to clone, explore, or contribute.
