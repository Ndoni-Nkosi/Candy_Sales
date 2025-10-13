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

A US national candy distributor called US candy distributor has been in business since 2021. Customers are able to place orders for chocolates, sweets, etc manufactured by different factories and get to choose how they want their order shipped to them.

Insights and recommendations are provided on the following key points:

- **Sales analysis**: An analysis on the historical sales patterns 
- **Product analysis**: An analysis on the best and worst performing products
- **Shipment and factory analysis**: An analysis on how the different factories have been performing overtime based on the number of units they get ordered

<sub>PowerBI dashboard can be downloaded here</sub><br/>

## Data Structure Overview

Data was collected from Maven Analytics where there were a number of dimension tables associated to the sales fact table. Dimension tables include Candy_factories, Candy_Products, Candy_Targets, and USzips.
The fact table for sales anlaysis is called Candy_Sales and consists of over 10 000 rows. </br>

During a process of data cleaning an additional tbale called Candy_Date was created to improve historical data analysis. </br>

<img width="993" height="541" alt="image" src="https://github.com/user-attachments/assets/efc9abaa-54d9-4cf1-a574-48726df1da7e" />


## Executive Summary
Since the opening of candy distributor sales have been increasing each year with a current profit percentage of 65.9%. A lot of customers are now opting to order chocolates and sweets from us lately, especially since we peaked in 2022 in the US. It has been evident that most orders are from the US rather than Canada with orders coming in are over 4000% more than Canada. These KPs are dicussed further in the report and opportunity areas are shown as well.

Below is an overview of the Power BI dashboard and additional graphs are included in the report below. </br>

<img width="1317" height="740" alt="image" src="https://github.com/user-attachments/assets/29d265b5-bcdf-4e58-9b7c-3220784d980e" />


## Insights Deep Dive

**Sales analysis**: </br>
- Sales have been increasing quite steadily over the years as we start off with a sales value of $1 065 in January 2021 and sales total now at $6 676 in December 2024. This results in us generating a profit of 65.9% since 2021. </br>
- Sales usually drops in non-seasonal times such as the months of January, and June to August. From the sales trend we see that sales drop in February which is a month popularly known for celebrating love (Valentines Day). As a candy distribution company we do not sell or promote any Valentine's like products or the factories that we distribute for do not have limited edition candies for seasons like Valentines.

**Product analysis**: </br>
- According to the product table we have made total sales of $141 784 thus far with the Wonka Bar - Triple Dazzle Caramel generating over $28k, accounting for 20% of our sales. </br>
- Although, we make great sales from the Wonka Bars, but Everlasting Gobstopper generates a greater profit of 80% for our business. The only dilemma is that it is one of the products that do not make much sales
- Our most popular products ordered by customers are the Wonka Bars with the Milk Cocolate flavour being the most ordered. Our least performing products include Fun Dip, Nerds, Everlasting Grasshopper, Hair Toffee, etc. </br>

<img width="667" height="422" alt="image" src="https://github.com/user-attachments/assets/66c53db1-4c8f-4ec7-b948-2627abaf7863" /> </br>


**Shipment and factory analysis**: </br>
- For factory analysis we notice a trend where factories such as Lots O' Nuts and Wicked Choccy's and our least performing factories are Sugar Shack, The Other Factory, and Secret Factory </br>
- Customers often opt for Standard Class shipping mode folowed by Second class. The least chosen shipping mode is Same Day Delivery

<img width="953" height="517" alt="image" src="https://github.com/user-attachments/assets/cfafe637-d9d0-4467-ada8-fbc39a7b8f66" /> </br>


## Recommendations
- To improve sales in the month of February we should look into selling limited edition candies for seasons like Valentines. This will also help improve Same Day shipping mode.
- Besides the Wonka Bars that generate high sales, we should try and promote products like Everlasting Gobstopper and Hair Toffee that generate a high profit percentage in sales for US candy distributor. This could improve the units ordered from Secret Factory and The Other Factory.
- Another option is that the least performing factories such as Secret Factory, The Other Factory, and Sugar Shack should create candies like Wonka Bars that generate good sales and profit. Manufacturing a new Wonka Bar flavour will help boost their units ordered and sales.

## Contact
Please contact me via email at ndoni.nkosi@yahoo.com
