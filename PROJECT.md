# Analytical-SQL-Project
----------------------------------------------
## PROJECT DESCRIPTION:
#### Customers have purchasing transactions that shall be monitored in order to observe each customer behavior to be able to target the customer in the most efficient and proactive way in the fututre to increase sales/revenue , enhance customers' retention and decrease churm.
----------------------------------------------
## DATASET SAMPLE: 
![17](https://user-images.githubusercontent.com/121814714/219868596-1c753d69-0a01-418c-b2f6-ba04acf57455.PNG)
-------------------------------------
## First of all: Asking some questions in order to gain some insights through answering these questions :
- [What is the number of orders and customers in the united kingdom?](#What-is-the-number-of-orders-and-customers-in-the-united-kingdom)
- [What is the number of orders per each invoice date?](#what-is-the-number-of-orders-per-each-invoice-date)
- [How many times each stockcode of a product is purchased?](#how-many-times-each-stockcode-of-a-product-is-purchased)
- [What is the quantity of items ordered per each unique invoicedate?](#what-is-the-quantity-of-items-ordered-per-each-unique-invoicedate)
- [Which invoicedates have the highest revenue?](#which-invoicedates-have-the-highest-revenue)
- [Who are the customers who buy the most from the store based on quantities?](#who-are-the-customers-who-buy-the-most-from-the-store-based-on-quantities)
- [Who are the highest paid customers of my store?](#who-are-the-highest-paid-customers-of-my-store)
--------------------------------------------------------------------------------
### What is the number of orders and customers in the united kingdom?
![5](https://user-images.githubusercontent.com/121814714/219780112-5642382d-248f-4343-b7fd-0674d7ff4a41.PNG)
### OUTPUT:
![6](https://user-images.githubusercontent.com/121814714/219780517-43a71629-6bce-4c2c-bcf9-150164fa2a6f.PNG)
--------------------------------------------------------------------------------
### What is the number of orders per each invoice date?
![3](https://user-images.githubusercontent.com/121814714/219775344-14dae10d-6ac6-4c8a-adb8-16f5abdd55de.PNG)
### OUTPUT SAMPLE:
![4](https://user-images.githubusercontent.com/121814714/219775526-9c02321d-0801-4ef0-b7f0-aec936e8423b.PNG)
-----------------------------------------------------------------------------
### How many times each stockcode of a product is purchased?
![7](https://user-images.githubusercontent.com/121814714/219783810-70bc17cf-2b74-4612-b571-3ad312618dae.PNG)
### OUTPUT SAMPLE:
![8](https://user-images.githubusercontent.com/121814714/219783913-aec4c8cb-9a52-4bf8-9790-215175722f8b.PNG)
------------------------------------------------------------------------------
### What is the quantity of items ordered per each unique invoicedate?
![9](https://user-images.githubusercontent.com/121814714/219785315-347d2338-88f5-4a54-a36c-d0d7844bbbeb.PNG)
### OUTPUT SAMPLE:
![10](https://user-images.githubusercontent.com/121814714/219785390-e1cae25a-214f-44f6-8794-8f8f7ff43693.PNG)
------------------------------------------------------------------------------
### Which invoicedates have the highest revenue?
![13](https://user-images.githubusercontent.com/121814714/219789207-39e6ba20-ed10-4176-80fc-724a3b7d7426.PNG)
### OUTPUT SAMPLE:
![14](https://user-images.githubusercontent.com/121814714/219789269-754e8f69-5508-4901-b9ae-06324223ec37.PNG)
------------------------------------------------------------------------
### Who are the customers who buy the most from the store based on quantities?
![11](https://user-images.githubusercontent.com/121814714/219786980-2a28df52-d8d8-4060-92e7-456769dee961.PNG)
### OUTPUT SAMPLE:
![12](https://user-images.githubusercontent.com/121814714/219787038-eb727cc9-ce3b-4957-beb8-61e631243038.PNG)
-----------------------------------------------------------------------------------
### Who are the highest paid customers of my store?
![15](https://user-images.githubusercontent.com/121814714/219791087-0b7e3f54-1e2d-4dc5-a8b0-90525db1783f.PNG)
### OUPUT SAMPLE:
![16](https://user-images.githubusercontent.com/121814714/219791140-00cae43e-67d3-43cc-b8b8-b4305bc03870.PNG)
---------------------------------------------------------------------------------------------------
## Quick Insights from the answers:
- All the customers' purchasing transactions take place only in the United Kingdom city, with 110 total cutomers that have done 717 orders.
- Most of the orders are ordered from 11:00 to 15:00 [Especially at 14:00].
- Proucts with stockcode 84077 , 84879 are ordered the most [11848 and 6095 times].
- Top 2 quantities of items were ordered in AUGUST month [4-8 and 11-8-2011].
- There is a strong correlatoin between the quanitity of items purchased and the returned revenue, As the top 2 highest amount of revenue were returnred at the same 2 days that were having the highest purchased quanitity of items [4-8 and 11-8-2011].
- Customers with customer id 12748, 12971 and 12921 are the top 3 ones who buy the most from the store.
- Customers with customer id 12931, 12748 and 12901 are the top 3 highest paid customers.
------------------------------------------------
## SECOND OF ALL: CUSTOMER SEGMENTATION 

### Trying to categorize customers based on 3 values:
 - Receny: The most recent transaction date in which the customer has purchased from the store.
 - Frequency: How many times has the customer bough from the store?
 - Monetary: How much has each customer paid for the store through transactions?
 ----------------------------------------------------
 ### #STEP 1 : Getting Recency Column:
 ![image](https://user-images.githubusercontent.com/121814714/219882932-66d352d1-4484-42d8-a718-47099f0ed931.png)
### OUTPUT SAMPLE:
![image](https://user-images.githubusercontent.com/121814714/219883009-7ac4c89b-79e8-42ea-9b97-831c260e7a72.png)


