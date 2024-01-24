## HR Data Analysis

### Problem Statement:  

The Human Resource (HR) department of a corporate company has all the data related to its employees. The HR manager wants to understand employee behaviour, retention rate, annual compensation, gender diversity, etc. As a Data Analyst, I have to develop a dashboard to answer all these questions.  

### Project Description:   

As a HR Data Analyst, my task here is to build an interactive dashboard to analyze the given employees dataset and come up with useful insights such as: the main reasons for employees to leave the company, employee retention rate and satisfaction score for each department over time, gender diversity and equality, employees’ age group, annual salary stats for each job role and department, total compensation given to management position for each year, etc.   

By analysing and understanding these results, we can know the reasons why employees’ have left the company and take necessary precautions/actions to retain valuable man power, understand how much the employees’ are happy and satisfied with the job role, annual salary and the company and come up with new processes/ideas which would empower them to work more efficiently and generate better output.   

### What I have learned by doing this project:   

1)	understood the data analytics pipeline – from data sourcing and extracting to deriving useful insights   
2)	connected to and extracted data from excel files  
3)	cleaned and transformed raw data using Power Query. Those are:
   
    a)	 promoted first row of table to Headers     
    b)	removed textual errors and inconsistencies in some columns    
    c)	created custom columns in different tables as per the requirement   
    d)	created conditional columns    
    e)	changed data types of different columns in the proper format    
    f)	created a new ‘Data Refresh’ table using ‘DateTime.LocalNow()’ function       
5)	data modelling – connected two tables and established a relationship between them            
6)	created various measures and calculated columns using DAX (Data Analysis Expressions). Here are some of the functions I have used in the project:  
   
    •	**CALCULATE** – to change the filter context of a measure/to give a new filter context to the measure    
    •	**DISTINCTCOUNT** – counts distinct values in a given column    
    •	**Direct Filter** – directly filters the table/column with a specific value in the column     
    •	**IF ELSE** – checks if the given condition is True/False and returns appropriate result(s)       

7)	created toggle buttons for switching between two visuals  
8)	used bookmark and selection   
9)	understood some important metrics related Human Resource (HR) department (employee retention rate, employee satisfaction score)  
10)	Choosing appropriate visuals to represent a particular metric/feature  
11)	Deploying the dashboard in Power BI service

### Data Analysis Report (Insights & Recommendations):     

**High-level Data Stats:**    

Total employees: 292  
Active Employees: 239  
Employees Left: 53  
Male employees: 154  
Female employees: 138  
Overall Retention Rate: 81.85%  
Overall Average Satisfaction Score: 3.84  

**Employer’s age group:**  

Most of the employees fall under the age group of 60s (27.4%), followed by 30s (23.97%) and 40s (22.60%)  

Men: When it comes to male employees, majority of them fall under the age group of 60s (29.87%), followed by 40s (24.03%) and 30s (23.38%)  

Female: On the contrary, majority of female employees fall under the age group of 30s (24.64%), followed by 60s (24.64%) and 50s (21.74%)  

**Gender % for Each Year:**   

The gender % of Female employees has increased year over year  

**Marital Status:**  

When it comes to marital status of the employees, majority of them are Single, followed by Married  

**Employee Retention Rate:**  

The years 2014, 2015 and 2016 have 100% employee retention rates. Year 2019 has the lowest retention rate with 83.68%.  

Administration department has 100% retention rate for all the years. Z Management also has 100% retention rate for all the years except for 2019 where only one employee has left.  

Sales department recorded the lowest retention rate for the year 2017 (83.33%). Production department has the lowest retention rates for the years 2018 (86.67%) and 2019 (79.33%)  

**Employee Count:**  

Production department has the highest employee count with 191 which is about 65% of total employees, followed by IT/IS with 56 employees  

**Average Annual Salary by Job Title:**  

Top 5 Job titles with highest average annual salary are: President & CEO ($189.5K), Director of Operations ($178.7K), BI Director ($177.5K), Director of sales ($170.9K), IT Director ($153.2K)     

Bottom 5 Job titles with lowest average annual salary are: IT Support ($41.80K), Administrative Assistant ($46.74K), Network Engineer ($55.60K), Accountant I ($57.21K), Production Technician I ($58.03K)      

**Average Employee Satisfaction Score by Job Title:**   

The job titles with highest average satisfaction score are: BI Director, CIO, Director of Operations, Enterprise Architect, IT Director with all accounting to satisfaction score of 5.0  

The job titles with lowest average satisfaction score are: Data Architect, IT Manager – Infra, President & CEO, Principal Data Architect, Software Engineering Manager with all accounting to satisfaction score of 3.0  

**Average Annual Salary & Bonus by Department:**  

The department with highest average annual salary is Z Department with $164K, followed by IT/IS with $73K. The department with lowest average annual salary is Sales – $66.4K. 

The department with highest average bonus amount also goes to Z Department with $17.2K. Surprisingly, the department with second highest average bonus amount is Sales with $11.5K. The department with lowest average bonus amount is Administration with $7.6K  

**Leave Reason:**  

The two main reasons for employees leaving the company are: Higher salary (15) and Performance issues (14), both of which account to about 55% of total employees left (53)  

**Average Employee Satisfaction Score by Department:**   

Z Management department has the highest average employee satisfaction score of 5.0 for the years 2015, 2017 and 2018  

Sales department records the highest average employee satisfaction score of 4.7, 4.17, and 4.0 for the years 2014, 2016 and 2019 respectively. On the contrary, it also records the second lowest score of 2.75 for 2015.   

**Recommendation:**   

Out of 53 people who left the company, 15 people have left due to higher paying jobs in other companies. So, it is recommended to re-evaluate the salary compensation of the employees according to their performance and work potential, and pay them accordingly. By doing this, we can retain talented individuals and can avoid unnecessary leaves.   

**Major factors contributing for Higher/Lower Satisfaction Score:**   

When the average Annual Salary increases by $30.8K, the average of employee satisfaction score increases by 0.18 and vice-versa.  

Similarly, when the Total Compensation increases by $33.4K, the average of employee satisfaction score increases by 0.10 and vice-versa.  

Surprisingly, when average Bonus Amount increases by $4.9K, the average of employee satisfaction score decreases by 0.21 and vice-versa.  






