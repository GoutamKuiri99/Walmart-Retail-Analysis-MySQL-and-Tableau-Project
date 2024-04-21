# 📊🎁 Walmart Retail Analysis MySQL & Tableau Project

![image](https://github.com/GoutamKuiri99/Walmart-Sales-Analysis-MySQL-Tableau-Project/assets/154737280/35ee831f-d665-4852-a557-19a8f7692a9f)

## About
This project aims to investigate Walmart's sales data to identify the best-performing branches and products, analyze sales trends for different products, and understand customer behavior. The goal is to examine how sales strategies can be enhanced and optimized. The dataset was acquired from the Kaggle Walmart Sales repository.

## Purposes Of The Project
The primary goal of this project is to explore Walmart's sales data to understand the various factors influencing sales and Profit at different store locations.
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

**5. What segment makes the most of our profits and sales ?**

This can be verified with the help of the following query and visualization:
![image](https://github.com/GoutamKuiri99/Walmart-Sales-Analysis-MySQL-Tableau-Project/assets/154737280/055bd673-a991-403c-81ee-c49ce2bd0061)

The Corporate segment brings in the most profit followed by Home Office, Small Business and Consumer is more sales but less profit will be generate. Let’s move on.

**9. How many customers do we have (unique customer IDs) in total and how much per region and state?**

This can be solved with the following;

![Screenshot 2024-04-21 101837](https://github.com/GoutamKuiri99/Walmart-Sales-Analysis-MySQL-Tableau-Project/assets/154737280/7a58c071-eea8-40c2-8a96-23a163b6af82)

We’ve had 795 customers between 2012 and 2015. 

**Regionally**, we had the following: 

![Screenshot 2024-04-21 102050](https://github.com/GoutamKuiri99/Walmart-Sales-Analysis-MySQL-Tableau-Project/assets/154737280/ad3dc6d7-63f4-4ae9-9c73-df0a208c0152)

We surely had customers moving around regions which explains why they all do not add up to 795. Since there could be double counting. The Central is the area where we have the biggest market of all.

**State wise**, here are the numbers: 

![Screenshot 2024-04-21 101953](https://github.com/GoutamKuiri99/Walmart-Sales-Analysis-MySQL-Tableau-Project/assets/154737280/e50da5d4-73e5-4f50-b9c9-ecb71437711e)

We have the most customers in California, Texas and Illinois. The areas where we have the least that passed by there are:

### Share
❖ Onto sharing our observations, below you will find a picture of picture of the interactive dashboard that represents the main the main KPIs and information on the collected Walmart data
Walmart data which was realized and demonstrated with with Tableau.

❖ The link to the interactive dashboard will be found under the screenshot below. Here are our findings:

❖ This is an in depth analysis of the Walmarts dataset. You will You will find interactive dashboards focused on the yearly yearly sales dashboards displaying data collected from 2012–2015.

❖ If there is mainly an interest in the yearly (timeline) data on profits, categories, sub categories, segments and products, then below you will find the direct link to the dashboard:

https://public.tableau.com/app/profile/goutam.kuiri/viz/Walmartretailproject/WalmartSalesDashboard


https://github.com/GoutamKuiri99/Walmart-Sales-Analysis-MySQL-Tableau-Project/assets/154737280/4a37e333-3d82-4446-83a8-633d6c8db61c


❖ This is an in depth analysis of the Walmarts dataset. You will find interactive dashboards focused on the yearly sales dashboards displaying data collected from 2012–2015. 

❖ If there is mainly an interest in the yearly (timeline) data on profits, categories, sub categories, segments and products, then below you will find the direct link to the dashboard:

### Conclusions and Future Recommendations:

**Steady Improvement in Profits and Sales**

❖ Our profits saw a steady improvement, with sales also experiencing growth despite a brief pause in 2012. Let's strive to maintain this momentum going forward.

**Focus on Q4 Profit Maximization.**

❖ Our peak in profitability consistently occurs during Q4.To maximize even more profits, we must make sure to have enough stock and push our marketing and customer service to make the most out of the October — December festive period.

**Regional Performance Analysis**

❖ The most performing regions are the Central then the South, East and West regions in that order. The West region brings in atleast $100,000 more in sales than the East region but still makes less profits than it. There is work to be done in the West region if we really want to keep that market. However, I believe it is better to take some of the resources in our West region to instead our Central region stores as we are more profitable there and could really establish ourselves as kingpin in that region.

**Market and Segment Insights**

❖ Illinios, Texas and Ohio are most profitable market and most present ones ones especially in terms of sales as states. We have to focus more on them. Our least Profitable markets are Montana, Delaware and West Virgina. Which I believe that we should decrease our presence there or even put a halt at our store locations there as sales in Montana and Delaware are in the $100,000s but are unable to convert to profits.

❖ Out of the 4 segments, The corporate segment brings in the most profit followed by Home office, Small Business and then Consumer. We must give more importance to the corporate segment even if all the 4 are profitable.

❖ Finally, for our clientele, we have 795 customers total, and we have the most customers in California, Texas and Illinois. California and Texas are pretty obvious, we have to be outstanding and be the best of what there is to offer in our respective niche.

**Thank you for your interest and time. Feel free to give your valuable suggestions and connect with me**   
https://www.linkedin.com/in/goutam-kuiri-949b632a6
