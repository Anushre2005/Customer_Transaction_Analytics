# INIT_TASK


Name:Anushree Revankar

## Summary:
This project processes customer transactions data across multiple CSVs, performing data loading, cleaning, merging, and aggregation.  
Calculations include revenue, profit margin, customer segmentation (RFM), product performance, and advanced operations like suspicious transaction detection and rolling window analysis.  
Also includes optimization and reusable functions such as Customer Lifetime Value (CLV) calculation.

## Approach:
- Filter transactions per customer
- Compute months since first purchase
- Apply monthly discount factor to each transaction's revenue
- Sum discounted revenues to get CLV

## Dependencies:
- pandas (for data manipulation and date handling)
- Python 3.9+
- numpy


