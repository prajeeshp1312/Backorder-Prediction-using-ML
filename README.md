# Backorder-Prediction-using-ML
The primary business problem that Back Order Prediction seeks to address is the issue of stockouts, where a business runs out of stock of a particular product. Classify the products whether they would go into Backorder (Yes or No) based on the historical data from inventory, supply chain and sales.


In the dataset we are provided with 23 columns(Features) of data.

  Sku(Stock Keeping unit) : The product id — Unique for each row so can be ignored 

 National_inv : The present inventory level of the product

  Lead_time : Transit time of the product 

 In_transit_qty : The amount of product in transit 

 Forecast_3_month , Forecast_6_month , Forecast_9_month : Forecast of the sales of the product for coming 3 , 6 and 9 months respectively 

 Sales_1_month , sales_3_month ,sales_6_month , sales_9_month : Actual sales of the product in last 1 , 3 ,6 and 9 months respectively

  Min_bank : Minimum amount of stock recommended 

 Potential_issue : Any problem identified in the product/part 

 Pieces_past_due: Amount of parts of the product overdue if any 

 Perf_6_month_avg , perf_12_month_avg : Product performance over past 6 and 12 months respectively 

 Local_bo_qty : Amount of stock overdue 

 Deck_risk , oe_constraint, ppap_risk, stop_auto_buy, rev_stop : Different Flags (Yes or No) set for the product

  Went_on_backorder : Product went on backorder( Target variable)
