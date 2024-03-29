# Capstone Project 1: Global Superstore Sales Record Analysis for the Year 2011-2014

![](https://github.com/omolola-A/Global-Superstore-Sales-Analysis/blob/main/superstore.avif)


## Introduction

A Power BI data analysis project to show the business performance over three years, placing more emphasis on the year 2014.
Global Superstore is a global online retailer based in New York, boasting a broad product catalog and aiming to be a one-stop shop for its customers. Global The superstore’s clientele, hailing from 147 different countries, can browse through an endless offering with more than 10,000 products. This large selection comprises three main categories: office supplies (e.g., staples), furniture (e.g., chairs), and technology (e.g., smartphones).
The analysis aims to analyze and draw out meaningful insight from the Superstore dataset which would aid management in making informed decisions to improve performance and profitability.
A Power BI data analysis project to show the business performance over three years, placing more emphasis on the year 2014.
Global Superstore is a global online retailer based in New York, boasting a broad product catalog and aiming to be a one-stop shop for its customers. Global The superstore’s clientele, hailing from 147 different countries, can browse through an endless offering with more than 10,000 products. This large selection comprises three main categories: office supplies (e.g., staples), furniture (e.g., chairs), and technology (e.g., smartphones).

## Data Source

The dataset was given by Digitaley Drive, to test my knowledge of Data Analysis, after completing data Bootcamp with them.

## Problem Statement

The analysis is to answer the following business questions:

1. - What are the three countries that generated the highest total profit for Global Superstore in 2014?
   - For each of these countries, find the products with the highest total profit. Specifically, what are the products’ names and the total profit for each product?

2. - Identify the 3 subcategories with the highest average shipping cost in the United States.

3. - Assess Nigeria’s profitability (i.e., total profit) for 2014. How does it compare to other African countries?
   - What factors might be responsible for Nigeria’s poor performance? You might want to investigate shipping costs and the average discount as potential root causes.

4. - Identify the product subcategory that is the least profitable in Southeast Asia. Note: For this question, assume that Southeast Asia comprises Cambodia, Indonesia, Malaysia, 
     Myanmar (Burma), the Philippines, Singapore, Thailand, and Vietnam. 
   - Is there a specific country in Southeast Asia where Global Superstore should stop offering the subcategory identified in 4a?

5. - Which city is the least profitable (in terms of average profit) in the United States? For this analysis, discard the cities with less than 10 Orders. b) Why is this city’s average 
     Is profit so low?
6. - Which product subcategory has the highest average profit in Australia?

7. - Who are the most valuable customers and what do they purchase?

## Method of Analysis

Power BI. Power BI is a powerful data analysis tool, used in performing different statistical analyses and visualization. For this project, I made use of: 

●	Power Query

●	Data Modeling

●	Data Cleaning

●	Data Visualization

## Modelling

The model is a three-table schema. There is one fact table that contains almost all the necessary information and 2-dimension tables. The dimension tables are all joined to the fact tables with many-to-many relationships.

![](https://github.com/omolola-A/Global-Superstore-Sales-Analysis/blob/main/Model.png)

## Visualisation and Analysis

The report contains 6 dashboards that answer the problem statements stated above.

### Visual 1

![](https://github.com/omolola-A/Global-Superstore-Sales-Analysis/blob/main/Global%20Superstore%20Sales%201.png)

The above shows the general overview of the report, showing the profits, sales, average shipping cost by subcategory, customers by revenue, and many more.

### Visual 2

![](https://github.com/omolola-A/Global-Superstore-Sales-Analysis/blob/main/Global%20Superstore%20Sales%202.png)

This focuses more on the year 2014. Giving answers to problem statements 1 and 2. As shown above, the three countries that generated the highest total profit for Global Superstore in 2014 are; the United States, India, and China with $93,501.51, $48,807.68, and $46,793.99 respectively.

The top three Products in the United States with the highest total profit with the total profit for each product are;

•	Canon image Class2200 Advance Copier = 15,679.96

•	Hewlett Packard LaserJet 3310 Copier = 3,623.94

•	GBC DocuBind TL300 Electric Binding System = 1,910.59

The top three Products in India with the highest total profit with the total profit for each product are:

•	Sauder Classic Bookcase, Traditional = 2,419.65	

•	Cisco Smart Phone, with Caller ID = 1,609.38	

•	Hamilton Beach Refrigerator, Red = 1,440.24

The three Products in China with the highest total profit with the total profit for each product are:

•	Sauder Classic Bookcase, Meatal = 1,463.07	

•	Bush Classic Bookcase, Mobile = 1,220.52	

•	HP Copy Machine, Color = 1,196.13		

Lastly, this visual shows the top 3 subcategories with the highest average shipping cost in the United States, which are:
•	Copiers	

•	Machines	

•	Tables

### Visual 3

![](https://github.com/omolola-A/Global-Superstore-Sales-Analysis/blob/main/Global%20Superstore%20Sales%203.png)

The above shows profit and loss made in Africa in 2014, comparing Nigeria with other African countries. A negative profit of 23,285.19 was made in Nigeria. This shows that Global Superstore made a loss despite recording a high quantity of orders sold when compared to other African countries.

The total profit is so low compared to other African countries. Also, the findings show that other African countries in the survey made positive profits.
Considering the shipping cost, the reason for Nigeria’s poor performance might be high shipping costs. Also, a high discount of over 50% was given to customers for products purchased compared to other African countries.

### Visuals 4 and 5

![](https://github.com/omolola-A/Global-Superstore-Sales-Analysis/blob/main/Global%20Superstore%20Sales%206.png) 

![](https://github.com/omolola-A/Global-Superstore-Sales-Analysis/blob/main/Global%20Superstore%20Sales%204.png)

Considering the profit made for each product subcategory in Southeast Asia, the following product subcategory are the least profitable for the following Southeast Asia Countries with their profits:

•	Cambodia – Storage ($1.26)

•	Indonesia – Table (-$10,680.28)

•	Malaysia – Label ($74.88)

•	Myanmar (Burma) – Tables (-$1,602.79)

•	Philippines - Tables (-$3,150.67)

•	Singapore – Fasteners ($57.39)

•	Thailand – Tables (-3,187.90)

•	Vietnam – Accessories (-$3,144.29)

Therefore, judging from the findings above, the least profitable product subcategory in Southeast Asia is Tables.

Global Superstore should stop supplying Tables to the following Southeast Asia due to non-profitability:

•	Indonesia

•	Myanmar (Burma)

•	Philippines

•	Thailand

### Visual 6

![](https://github.com/omolola-A/Global-Superstore-Sales-Analysis/blob/main/Global%20Superstore%20Sales%205.png)

In terms of average profit, the city with the least profit in the United States is **BETHLEHEM** with **-$200.62**. This might be to the very high discount of 70% given on the most ordered product subcategory. Also investigating the cost of shipping, it was observed that the shipping cost was high and a binder was also returned.

From the average profit in Australia considered, the highest product subcategory that has the highest average profit in Australia is:
**_Appliances_** with an average profit of **_$139.01_**

Most valuable customers are the customers who make the company make the most profit. They are customers that buy more. And for Global Superstores, the most valuable customers are:

- Tamara Chand
- Raymond Buch
- Sanjit Chand

## Conclusion and Recommendation

### Recommendations

- Global Superstore should look for a way to reduce the cost of shipping products, this is to reduce cost, and maximize profits. They can find an alternative shipping company with a lower rate, or negotiate a reduction with the existing one.
- They should stop the supply of Tables to Some Southeast Asia Countries, and other Countries where loss has been recorded.
- Global Superstore should reduce the % discount on products ordered by Nigerians to improve on the profits that will made in the subsequent years.
- Customers should be encouraged, maybe by rewarding the most valuable customers.
- Lastly, research should be conducted in countries with high profits, to know the factors responsible for such, and probably implement the key factors found responsible for the high profits in countries with lesser profits.

### Conclusion

Finally, the analysis of the Global Superstore sales performance spanning from 2011 to 2014 offers valuable insights into the dynamics of the retail industry during this period. Through meticulous examination of sales trends, customer behavior, and product performance, we have uncovered patterns and opportunities that can inform strategic decision-making. From identifying profitable market segments to optimizing inventory management, the findings from this project serve as a foundation for driving business growth and enhancing operational efficiency. Moving forward, leveraging these insights will be crucial in navigating the evolving landscape of the Global Superstore market and staying ahead of the competition.



*Thanks.*  _Below is the link to my GitHub Account_

https://github.com/omolola-A


