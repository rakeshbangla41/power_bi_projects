## Northwind Traders Gourmet Supply Data Analysis   

### You can view the live dashboard here: [Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiN2ExYWNjZWQtYTkzNC00YjA1LWJkYzMtMDc1ZGFkZWVkNWRlIiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9) or [novyPro Dashboard](https://www.novypro.com/project/northwind-traders-gourmet-supply-data-analysis-%7C-maven-analytics-data-challenge)

  
### Problem Statement:    

Northwind Traders is a global import and export company which supplies gourmet food products to restaurants, hotels, cafes, and food retailers around the world. The top management wants to understand the company's performance over time. As a Data Analyst, I have been the task to develop a Power BI dashboard that delivers meaningful insights, facilitating informed and data-driven decision-making.

### Project Description:   

Within this project, I have designed a comprehensive KPI dashboard intended for the executive team's analysis of key metrics related to both sales and the supply chain. These metrics include:

a) Sales-related metrics:   

* Total sales revenue  
* Customer and product performance
* Sales revenue trends per year
* Identification of most valued customers and products
* Recognition of top-performing countries and cities contributing to order amount
* Aggregation of total quantities sold and total order amount for each category

b) Supply chain-related metrics:

* Gourmet product supply destinations worldwide
* Total freight cost analysis
* Identification of countries with the highest and lowest freight costs
* On-time delivery percentage (OTD%)
* Overview of orders shipped to various countries by the shipping company
     
  
This dashboard provides valuable insights and recommendations which would help the company to optimize their sales and supply chain strategies, improve customer satisfaction, and maximize Return on Investment (ROI).    

### What I have learned by doing this project:   

1)	understood the entire data analytics pipeline – from data sourcing and extracting to deriving useful insights   
2)	connected to and extracted data from CSV files  
3)	cleaned and transformed raw data using Power Query. Those are:   
    a)	trimmed blank and trailing spaces,   
    b)	removed textual inconsistencies in some columns  
    c)	promoted first row of table to Headers  
    d)	changed data types of different columns in the proper format  
    e)	created two tables (‘countries and cities’ table and ‘order amount and quantity sold’ table) using columns from other tables   
    f)	created custom columns in different tables as per the requirement  
    g)	created a new ‘Data Refresh’ table using ‘DateTime.LocalNow()’ function  
4)	data modelling – connected different tables and established a relationship between them  
5)	created various measures and calculated columns using DAX (Data Analysis Expressions). Here are some of the functions I have used in the project:  

    •	**CALCULATE** – to change the filter context of a measure/to give a new filter context to the measure  
    •	**FILTER** – to filter a given table or a subset/resultant table from a measure  
    •	**LOOKUPVALUE** – looks for a particular value based on specific criteria and returns the corresponding result  
    •	**DATEDIFF** – gives difference between two dates in days, months, etc.  
    •	**DISTINCTCOUNT** – counts distinct values in a given column  

6)	Employed bookmarks and selections for seamless switching between visuals
7)	Acquired an understanding of critical metrics related to the supply chain, global import, and export, including freight cost and on-time delivery percentage.  
8)  Applied principles of choosing appropriate visuals, formatting, and effective dashboard design.
9)  Successfully deployed the project in Power BI service



### Data Analysis Report (Insights & Recommendations):   

**High-level data stats:**   

Total Orders: 830  
Total Quantities Sold: 51.32K units  
Total Order Amount: $1.27M  
Total Freight Cost: $64.94K   
Total Sales Revenue: $1.20M  
On-Time Deliveries %: 95.4%  

**Insights:**  

**Key/Top Customers by order amount:**  

QUICK-Stop (Germany), Ernst Handel (Austria), Save-a-lot Markets (USA), Rattlesnake Canyon Grocery (USA), Hungry Owl All-Night Grocers (Ireland) are the top 5 customers w.r.t order amount. These 5 companies have contributed to $0.42 M out of $1.27 M total order amount.   

**Best/Least selling Products by order amount:**  

Côte de Blaye (Beverages), Thüringer Rostbratwurst (Meat & Poultry), Raclette Courdavault (Dairy Products), Tarte au sucre (Confections), Camembert Pierrot (Dairy Products) are the top 5 best-selling products accounting to $0.39 M out of $1.27 M total order amount.  

Chocolade (Confections), Geitost (Dairy Products), Genen Shouyu (Condiments), Laughing Lumberjack Lager (Beverages), Longlife Tofu (Produce) are the least 5 selling products. 

**Best/Least selling Product Categories:**  

Beverages ($267.87K), Dairy Products ($234.51K) and Confections ($167.36K) are the top 3 best selling product categories.  

Grains & Cereals ($95.74K) and Produce ($99.98K) are the least selling categories.  

**Sales Revenue:**  

The highest sales revenue is from the year 2014 ($584.62K), followed by year 2015 ($418.43K) and 2013 ($197.80K).  

The peak months for sales revenue are from: 2014 December to 2015 April contributing to about $468.38K. The highest sales month is 2015 April (117.41K).  

The lowest sales months are: 2015 May ($17.65K), 2013 August ($24.09K), 2013 July ($26.57K)  

**Best/Least performing Countries/Cities:**  

Top 5 countries with the highest sales revenue: USA ($231.81K), Germany ($219.00K), Austria ($120.61K), Brazil ($102.05K), France ($77.12K)  

Bottom 5 Countries with least sales revenue: Poland ($3.36K), Norway ($5.46K), Argentina ($7.52K), Portugal ($10.83K), Italy ($14.91K)  

Top 5 performing cities wrt sales revenue: Cunewalde ($104.67K), Graz ($98.67K), Boise ($97.68K), Rio de Janeiro ($50.27K), London ($50.23K)  

Least 5 performing cities wrt sales revenue: Walla Walla ($0.34K), Vancouver ($0.51K), Barcelona ($0.80K), Caracas ($1.42K), Reims ($1.42K)  

**Shipping:**  

Out of 830 total orders, most number of orders were shipped by United Package (326), followed by Federal shipping (255) and Speedy Express (249)  

**Freight Cost:**  

Top 5 countries with highest overall freight cost: USA ($13.77K), Germany ($11.28K), Austria ($7.39K), Brazil ($4.88K), France ($4.24K)  

Top 5 countries with lowest overall freight cost: Poland ($0.18K), Norway ($0.28K), Argentina ($0.60K), Portugal ($0.64K), Spain ($0.86K)  

**Discontinued Products:**  

Some of the discontinued products like Thüringer Rostbratwurst, Alice Mutton, Rössle Sauerkraut have brought in high order amounts. We have to re-consider these products for a re-launch or if not have to find out the reasons why these were discontinued in the first place.  

**Discounted Products:**  

Products like Côte de Blaye, Thüringer Rostbratwurst, Raclette Courdavault, Tarte au sucre, on which higher discounts were offered, are also the same products which brought in higher order amounts.  

**Countries supplied:**  

Northwind traders has all it’s customer base in: Europe, North America and South America.  

Most of the countries we supply to, are in Europe.  

Since, Europe is a very big market, we can think of expanding our business to other countries as well based on the demand and supply of gourmet food products in those countries. A survey or a research could help alot in deciding about business requirements.  




