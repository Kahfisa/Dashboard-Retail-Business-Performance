# Dashboard-Retail-Business-Performance

## Introduction
This project presents an interactive dashboard analyzing retail performance, including trend analysis, regional performance, and product performance. It explores monthly sales and profit trends, evaluates product and category performance, sales and category distribution across cities, and examines the impact of discounting on profit.


## Tools
- Python
- Looker Studio

## Dataset
|Dataset        |Column                        |Description                                                     |
|---------------|------------------------------|----------------------------------------------------------------|
|superstore     |row_id                        |Unique number for each data row.
|               |order_id                      |Unique ID for each order.
|               |order_date                    |The date when the order was placed by the customer.  
|               |ship_date                     |The date when the shipment was made by the store.
|               |ship_mode                     |The shipping method used.
|               |customer_id                   |Unique ID for each customer.
|               |customer_name                 |The name of the customer.
|               |segment                       |Customer category based on market type.
|               |country                       |The country where the customer is located.
|               |city                          |The city where the customer is located.
|               |state                         |The state where the customer is located.
|               |postal_code                   |The postal code of the customer's location.
|               |region                        |The geographic region within the country.
|               |product_id                    |Unique ID for each product.
|               |category                      |The main product category.
|               |subcategory                   |The product subcategory.
|               |product_name                  |The name of the product.
|               |sales                         |Total sales value for the item.
|               |quantity                      |The number of product units sold in the transaction.
|               |discount                      |The percentage discount applied.
|               |profit                        |Net profit from the product sale.

Link: https://www.kaggle.com/datasets/vivek468/superstore-dataset-final

## Business Question
- How do monthly sales and profit trends change over time?
- Which cities generate the highest and lowest profit?
- Which product categories show strong or weak monthly sales performance?
- Which products generate the highest sales and order volume? 
- How does discounting affect profit?
- How are sales and product categories distributed across different cities?
- 

## Dashboard Preview
<img width="1047" height="763" alt="image" src="https://github.com/user-attachments/assets/aa7324c2-cb22-4689-a7e9-99d77d0a6d53" />

<img width="1046" height="766" alt="image" src="https://github.com/user-attachments/assets/04484961-0fa0-4c7d-92c1-34b8bbc8c48a" />


## Insight
- Total sales experienced a slight decline of 2.82% from 2014 to 2015. However, sales then increased sharply by 29.4% in 2016 and continued to grow by 20.4% in 2017, indicating strong business growth and a recovery after the initial decline
- The highest profits are concentrated in the American region, as indicated by the larger bubble sizes. Cities with the largest bubbles show significant profit contributions, highlighting these areas as key potential markets that should be prioritized in business strategy.
- The Technology and Office Supplies categories experienced a decline in sales in 2015, but both showed significant growth in 2016 and 2017. Meanwhile, the Furniture category recorded stable and consistent growth each year, with an average increase of 12.63%.
- Products such as staples, staple envelope, and easy-staple paper record the highest sales volume, but their sales value remains relatively low. This indicates that these items fall into the high volume but low price category, contributing minimally to total revenue despite frequent purchases.
- Products that receive large discounts do not have a significant impact on profit, indicating the need to evaluate the discount strategy.
- The sales distribution by category shows different patterns across regions. Technology products are primarily concentrated in the Americas, while Furniture is more dominant in the Americas and Europe, although it rarely achieves high sales. The Office Supplies category has a wider distribution across the Americas, Europe, and Australia, and more frequently generates high sales. These patterns indicate that market potential varies by category, suggesting that sales strategies should be tailored based on both region and product type.
