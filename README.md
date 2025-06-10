# Task6 : Analyze monthly revenue and order volume

## Approach
1. Created a sample `online_sales` table with columns `order_id`, `order_date`, `amount`, and `product_id`.
2. Inserted 10 sample records for 2023 and 2024.
3. Wrote an SQL query to:
   - Extract year and month using `EXTRACT`.
   - Calculate total revenue with `SUM(amount)`.
   - Count unique orders with `COUNT(DISTINCT order_id)`.
   - Group by year and month, sorted chronologically.
   
## Results
The results table shows monthly revenue and order volume for 2023 and 2024.
