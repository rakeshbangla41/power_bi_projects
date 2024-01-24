## Northwind Traders Gourmet Supply Data Analysis   

  
### Problem Statement:    

Northwind Traders is a global import and export company which supplies gourmet food products to restaurants, hotels, cafes, and food retailers around the world. The top management wants to understand the company's performance over time. As a Data Analyst, I have been the task to develop an interactive dashboard which should provide valuable insights about the company's overall progress.

### Problem Description:   

In this project, I have developed a high-level KPI dashboard for the executive team to analyse key metrics such as: customer and product performance, total revenue generated, sales revenue trend for each year, best performing countries and cities around the world contributing to order amount, total quantities sold and total order amount by each category, countries with the highest and lowest freight cost, on-time delivery percentage, etc.     
  
This dashboard provides valuable insights and recommendations which would help the company to optimize their sales and supply chain strategies, improve customer satisfaction, and maximize Return on Investment (ROI).    

### What I have learned by doing this project:   

1)	understood the data analytics pipeline – from data sourcing and extracting to deriving useful insights   
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

6)	created toggle buttons for switching between two visuals  
7)	used bookmark and selection   
8)	understood some important metrics related to supply chain and global import & export (freight cost, on-time delivery %, etc.)  
9)	Choosing the right visuals and formatting and dashboard designing principles  
10)	Deploying in Power BI service

    

