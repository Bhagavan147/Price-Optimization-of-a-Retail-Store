# Price Optimization of a Retail Store

## **Objective**  
TrendElite, a multi-channel clothing retailer, seeks to enhance revenue and competitiveness by optimizing its pricing strategy. The goal is to determine optimal prices that **maximize revenue while maintaining strong customer demand**.  

## **Dataset Description**  

| **Feature**                  | **Description**  |  
|------------------------------|----------------------------------------------------------------|  
| **product_id**               | Unique identifier for each product.  |  
| **product_category_name**    | Name of the category the product belongs to.  |  
| **month_year**               | Month and year of the transaction or data recording.  |  
| **qty**                      | Quantity of the product sold in a given transaction.  |  
| **total_price**              | Total price of the product (qty × unit_price, including taxes/discounts).  |  
| **freight_price**            | Average freight cost associated with the product.  |  
| **unit_price**               | Average unit price of a single product.  |  
| **product_name_length**      | Number of characters in the product name.  |  
| **product_description_length** | Number of characters in the product description.  |  
| **product_photos_qty**       | Number of photos available for the product.  |  
| **product_weight_g**         | Weight of the product in grams.  |  
| **product_score**            | Average rating based on product quality, popularity, or other factors.  |  
| **customers**                | Number of customers who purchased the product.  |  
| **weekday**                  | Number of weekdays in the transaction month.  |  
| **weekend**                  | Number of weekends in the transaction month.  |  
| **holiday**                  | Number of holidays in the transaction month.  |  
| **month**                    | Month in which the transaction occurred.  |  
| **year**                     | Year in which the transaction occurred.  |  
| **s**                        | Effect of seasonality on sales.  |  
| **Volume**                   | Product volume.  |  
| **Comp_1**                   | Price of competitor 1.  |  
| **Ps1**                      | Product rating of competitor 1.  |  
| **Fp1**                      | Freight price of competitor 1.  |  
| **Comp_2**                   | Price of competitor 2.  |  
| **Ps2**                      | Product rating of competitor 2.  |  
| **Fp2**                      | Freight price of competitor 2.  |  
| **Comp_3**                   | Price of competitor 3.  |  
| **Ps3**                      | Product rating of competitor 3.  |  
| **Fp3**                      | Freight price of competitor 3.  |  
| **Lag_price**                | Previous month's price of the product.  |  

## **Approach**  
1. **Data Exploration & Preprocessing**: Clean and analyze key variables, including product attributes, customer behavior, and sales trends, while handling outliers, missing values, and duplicates.  
2. **Descriptive Analysis & Feature Engineering**: Generate insights using visualizations and statistics; create new features such as **profit, profit margin, revenue, and time-based factors (weekend/holiday indicators)**.  
3. **Pricing Model Development**: Utilize **machine learning models** to predict optimal prices by analyzing factors like **production costs, demand elasticity, and competitor pricing**.  
4. **Scenario Testing & Impact Assessment**: Evaluate different pricing strategies and their effects on revenue, ensuring alignment with **business goals and market positioning**.  
5. **Final Strategy Recommendation**: Identify **optimal product prices** based on data-driven insights, balancing **profitability, demand, and competitive positioning**.  

### **Outcome**  
By implementing **optimized pricing strategies**, TrendElite can achieve higher revenue, improved market positioning, and increased customer engagement while maintaining a competitive edge in both online and physical retail spaces.
