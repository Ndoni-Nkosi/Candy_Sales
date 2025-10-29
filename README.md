# Candy Sales project
A sales analysis is done on US candy distributor data from Maven Analytics consisting of synthetic data.

## Table of Contents

- [Background and Overview](#BackgroundandOverview)
- [Data Structure Overview](#DataStructureOverview)
- [Executive Summary](#ExecutiveSummary)
- [Insights Deep Dive](#InsightsDeepDive)
- [Recommendations](#Recommendations)
- [Contact](#contact)

## Background and Overview

A U.S. candy distributor, known as US Candy Distributor, has been operating since 2021. Customers can place orders for chocolates, sweets, and other confections manufactured by various factories, with options for how they would like their orders to be shipped.

Insights and recommendations are provided on the following key points:

- **Sales Analysis**: An analysis of historical sales patterns.
- **Product Analysis**: An analysis of the best and worst performing products.
- **Shipment and Factory Analysis**: An analysis of how the different factories have been performing over time based on the number of units ordered.

<sub>PowerBI dashboard can be downloaded here</sub><br/>

## Data Structure Overview

Data was collected from Maven Analytics, which included several dimension tables linked to the sales fact table. The dimension tables are Candy_Factories, Candy_Products, Candy_Targets, and US_Zips. The fact table used for sales analysis is named Candy_Sales and contains over 10,000 rows. </br>

As part of the data cleaning process, an additional table called Candy_Date was created to enhance historical data analysis.</br>

<img width="992" height="542" alt="image" src="https://github.com/user-attachments/assets/27a399d4-3f7e-476b-84db-eade11413061" />



## Executive Summary

Since the launch of the distribution company, sales have consistently increased each year, resulting in a current profit margin of 65.9%. Recently, we have seen a significant rise in customers ordering chocolates and sweets from us, particularly following our peak in sales in the USA in 2022. It is clear that the majority of orders are coming from the US, which are over 4000% higher than those from Canada. The key performance indicators (KPIs) and areas for improvement are discussed in further detail in the report.

Below is an overview of the Power BI dashboard along with additional graphs included in the report. </br>

<img width="1317" height="740" alt="image" src="https://github.com/user-attachments/assets/29d265b5-bcdf-4e58-9b7c-3220784d980e" />


## Insights Deep Dive

**Sales analysis**: </br>
- Sales have been steadily increasing over the years. We started with a sales value of $1,065 in January 2021, and as of December 2024, our total sales have reached $6,676. This represents a profit increase of 65.9% since 2021.</br>
- However, we typically see a drop in sales during non-peak seasons, specifically in January and from June to August. Notably, there is a decline in sales during February, a month known for celebrating love due to Valentine's Day. As a candy distribution company, we neither sell nor promote any products related to Valentine's Day, and the factories we work with do not offer limited edition candies for seasons like Valentine's.

**Product analysis**: </br>
- According to the product table, we have made a total of $141,784 in sales so far, with the Wonka Bar - Triple Dazzle Caramel generating over $28,000. This accounts for 20% of our overall sales. </br>
- While the Wonka Bars contribute significantly to our sales, the Everlasting Gobstopper has a much higher selling price profit percentage of 80% for our business. The challenge, however, is that it does not sell as well as some other products.
- Our most popular product among customers is the Wonka Bar, with the Milk Chocolate flavor being the top seller. On the other hand, our least performing products include Fun Dip, Nerds, Everlasting Grasshopper, and Hair Toffee, among others. </br>

<img width="667" height="422" alt="image" src="https://github.com/user-attachments/assets/66c53db1-4c8f-4ec7-b948-2627abaf7863" /> </br>


**Shipment and factory analysis**: </br>
- Factories such as Lots O' Nuts and Wicked Choccy's sell more product units compared to lower-performing factories like Sugar Shack, The Other Factory, and Secret Factory.  </br>
- Customers tend to prefer Standard Class shipping, followed by Second Class. The least popular option is Same Day Delivery, likely because it tends to be more expensive than Standard Class. This suggests that many of our customers are budget-conscious and willing to wait a few days for their orders.

<img width="953" height="517" alt="image" src="https://github.com/user-attachments/assets/cfafe637-d9d0-4467-ada8-fbc39a7b8f66" /> </br>


## Recommendations
- To boost sales in February, we should consider offering limited edition candies for occasions like Valentine's Day. This strategy could also enhance the Same Day shipping option.
- In addition to the high-selling Wonka Bars, we should promote items like Everlasting Gobstopper and Hair Toffee, which have a high profit margin for our U.S. candy distribution. This could increase the order volumes from Secret Factory and The Other Factory.
- Another strategy is to encourage the least productive factories, such as Secret Factory, The Other Factory, and Sugar Shack, to develop new candies similar to Wonka Bars that yield strong sales and profits. Manufacturing a new flavor of Wonka Bar could significantly boost their order volumes and overall sales.

## Contact
Please contact me via email at ndoni.nkosi@yahoo.com
