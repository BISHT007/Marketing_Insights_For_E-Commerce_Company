# Marketing_Insights_For_E-Commerce_Company


### Business Context:
One of the leading E-Commerce Company would like to get marketing insights from the data to  
define marketing strategies going forward.  


### Available Data: 
Transaction data has been provided for the period of 1st Jan 2019 to 31st Dec 2019. The below data
sets have been provided.
#### Online_Sales.csv: This file contains actual orders data (point of Sales data) at transaction level with below variables.  
CustomerID: Customer unique ID  
Transaction_ID: Transaction Unique ID  
Transaction_Date: Date of Transaction  
Product_SKU: SKU ID – Unique Id for product  
Product_Description: Product Description  
Product_Cateogry: Product Category  
Quantity: Number of items ordered    
Avg_Price: Price per one quantity    
Delivery_Charges: Charges for delivery    
Coupon_Status: Any discount coupon applied  
#### Customers_Data.csv: This file contains customer’s demographics.  
CustomerID: Customer Unique ID  
Gender: Gender of customer  
Location: Location of Customer  
Tenure_Months: Tenure in Months  
#### Discount_Coupon.csv: Discount coupons have been given for different categories in different months
Month: Discount coupon applied in that month  
Product_Category: Product category  
Coupon_Code: Coupon Code for given Category and given month  
Discount_pct: Discount Percentage for given coupon  
#### Marketing_Spend.csv: Marketing spend on both offline & online channels on day wise.  
Date: Date  
Offline_Spend: Marketing spend on offline channels like TV, Radio, NewsPapers, Hordings etc  
Online_Spend: Marketing spend on online channels like Google keywords, facebook etc
#### Tax_Amount.csv: GST Details for given category  
Product_Category: Product Category  
GST: Percentage of GST  

 
### Key Definitions:
-> Invoice Value: Invoice Value =(( Quantity*Avg_price)*(1-Dicount_pct)*(1+GST))+Delivery_Charges  
-> Average order value = Revenue / Transaction per customer  
-> Profit Margin Profit margin is the commonly used profitability ratio. It represents how much percentage of total sales 
   has earned as the gain.  
-> Purchase Frequency is the average number of purchases made by a customer over a defined period  
   of time (typically one month or one year). It is the sum of total number transactions divided by total  
   number customers.  
-> Repeat rate shows you the percentage of your current customer base that has come back to shop
   again.  
-> Churn Rate is the annual percentage rate at which customers stop subscribing.  
   Customer lifetime value, lifetime customer value, or life-time value is a prediction of the net  
   profit/revenue attributed to the entire future relationship with a customer.  

   
## Business Objective:
The e-commerce company is expecting below analysis using the data    
#### 1. Calculate Invoice amount or sale_amount or revenue for each transaction and item level   
 Invoice Value =(( Quantity*Avg_price)*(1-Dicount_pct)*(1+GST))+Delivery_Charges  
#### 2. Perform Detailed exploratory analysis  
 Understanding how many customers acquired every month  
 Understand the retention of customers on month on month basis  
 How the revenues from existing/new customers on month on month basis  
 How the discounts playing role in the revenues?  
 Analyse KPI’s like Revenue, number of orders, average order value, number of  
customers (existing/new), quantity, by category, by month, by week, by day etc…  
 Understand the trends/seasonality of sales by category, location, month etc…  
 How number order varies and sales with different days?  
 Calculate the Revenue, Marketing spend, percentage of marketing spend out of revenue, Tax, percentage of delivery charges 
  by month.  
 How marketing spend is impacting on revenue?  
 Which product was appeared in the transactions?  
 Which product was purchased mostly based on the quantity?  
#### 3. Performing Customer Segmentation  
 Heuristic (Value based, RFM) – Divide the customers into Premium, Gold, Silver,Standard customers and define strategy on 
  the same.   
 Scientific (Using K-Means) & Understand the profiles. Define strategy for each segment.  
#### 4. Predicting Customer Lifetime Value (Low Value/Medium Value/High Value)  
 First define dependent variable with categories low value, medium value, high value using customer revenue.    

