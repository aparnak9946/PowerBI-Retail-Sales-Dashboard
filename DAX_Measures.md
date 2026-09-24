# DAX Measures

## Total Sales

```DAX
Total Sales = SUM(retail_sales_powerbi[Sales])



Total Profit = SUM(retail_sales_powerbi[Profit])

Total Orders = DISTINCTCOUNT(retail_sales_powerbi[Order_ID])

Total Customers = DISTINCTCOUNT(retail_sales_powerbi[Customer_ID])

Profit Margin = DIVIDE([Total Profit], [Total Sales], 0)


