# PowerBI-Sales-Performance-Dashboard

https://github.com/clementemma10/PowerBI-Sales-Performance-Dashboard-/blob/main/dashboard.png

Sales Performance Dashboard: Regional, Product and Customer Insights

I created an interactive Power BI report from a real public dataset (Kaggle Sample Sales Data: 2,823 order lines, 307 orders, 19 countries, Jan 2003 to May 2005) to identify where revenue originates and how it evolves through time.

Main results: Total revenue reached $10.03M. EMEA was the strongest region at $5.0M, while the USA ranked first by country with $3.6M. November is the highest month in every year, representing 29% of 2003 revenue and 23% of 2004 revenue. Revenue increased 34% from 2003 to 2004, and January to May 2005 was roughly 36% higher than the same period in 2004. Shipping was completed for 93% of orders, and just 4 were cancelled. A single customer, Euro Shopping Channel, contributed roughly 9% of total revenue.

Data preparation: Because the PRICEEACH column was limited to 100 on 46% of rows, I based revenue calculations on SALES. Missing territories in USA and Canada orders were assigned to North America. Since the dataset does not include cost information, profit was not computed.

Tools used: Excel, Power BI, Power Query, DAX.
