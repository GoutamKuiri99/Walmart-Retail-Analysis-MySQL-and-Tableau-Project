# 📊🎁 Walmart Sales Analysis MySQL & Tableau Project

![image](https://github.com/GoutamKuiri99/Walmart-Sales-Analysis-MySQL-Tableau-Project/assets/154737280/35ee831f-d665-4852-a557-19a8f7692a9f)

## About
This project aims to explore the Walmart Sales data to understand top performing branches and products, sales trend of of different products, customer behaviour. The aims is to study how sales strategies can be improved and optimized. The dataset was obtained from the Kaggle Walmart Sales. 
## Purposes Of The Project
The major aim of thie project is to gain insight into the sales data of Walmart to understand the different factors that affect sales of the different branches.
## About Data
In this phase, we will identify and assess the features of
our Walmart Dataset:

• It comes with 8400 rows with 8400 being pure data and
the other one row being the column headers. It contains
data recorded between the 1st of January 2012 (the first
order date) to the 30th of December 2015 (the last
shipping date). (The last order date is the 30th of
December 2015, so we will instead use the order dates
range to represent our 4 years of business)

• It contains the data of 795 customers.
Query The data contains the 23 columns namely; City , Customer
Name , Customer Segment , Discount , Number of Records , Order
Date , Order ID , Order Priority , Order Quantity , Product Base
Margin , Product Category , Product Container , Product Sub
Category , Profit , Region , Row ID , Sales , Ship Date , Ship Mode ,
Shipping Cost , State , Unit Price , Zip Code .

• Moving on to the data processing, we will use Excel , Power for
cleaning .
## Analysis List
**1. What are total sales and total profits of each year?**
   
   The years were grouped by order date, so we can observe data for the
year 2012,2013,2014 and 2015.

![image](https://github.com/GoutamKuiri99/Walmart-Sales-Analysis-MySQL-Tableau-Project/assets/154737280/8b7992ea-6a82-464d-9f75-b70851bc3d08)

**2. What are the total profits and total sales per quarter?**

Now this table will aid us in knowing what quarters were the most profitable to us from 2012–2015. This can help to pave the way for investment and marketing strategies. 

![Screenshot 2024-04-20 114354](https://github.com/GoutamKuiri99/Walmart-Sales-Analysis-MySQL-Tableau-Project/assets/154737280/f52f451a-5dd5-41ee-9706-ea8793cd11d1)

The data above shows that the period of October, November and December consistently emerge as our peak selling months , generating the highest profits. Analyzing this table provides valuable insights for crafting operational strategies, akin to observing a stock market rally from January to December, followed by a downturn in the initial three months. Let’s get into the regions.

**3. What region generates the highest sales and profits ?**

![image](https://github.com/GoutamKuiri99/Walmart-Sales-Analysis-MySQL-Tableau-Project/assets/154737280/945f0672-55a7-43ad-b303-2bd71d9b9966)

We can observe above that the Central region is the one with the most sales and brings us in the highest profits. The south region is pretty good looking for our company too because less sales but more profit generate. Those 2 regions are definitely areas of interest if we want to maximize our profits and expand our business. Concerning the East region, we do not gain a lot of revenue but still the profits are there. It is the West region that is quite alarming as we generate way more revenue than the East region but do not make at least the same profits over there. The West region should be on our watchlist as we could start to think on how we could maybe put our resources in the other regions instead.

**4. What category generates the highest sales and profits ?**

First, let’s observe the total sales and total profits of each category with their profit margins:

![Screenshot 2024-04-20 121326](https://github.com/GoutamKuiri99/Walmart-Sales-Analysis-MySQL-Tableau-Project/assets/154737280/7f47e530-88b7-4c3a-b114-41d920172daf)

Among the three categories, it's evident that Technology and Office Supplies stand out for their robust profitability. Plus they seem like a good investment because of their profit margin. To gain deeper insights, let's analyze the regions with the highest total sales and profits within each category. This will provide us with a clearer understanding of each category's regional performance and potential for growth.
