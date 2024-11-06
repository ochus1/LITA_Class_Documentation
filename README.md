# **LITA_Class_Documentation**

# **[ClassWork 1](#project-title-copier-sales-report)**

# **[Project 1](#project-title-sales-data-analysis)**

# **[Project 2](#project-title-customers-subscription-analysis)**

### Project Title: Copier Sales Report

![copier pix](https://github.com/user-attachments/assets/97fc5aec-6f80-4f9b-90d6-44bb5d0429d9)


[Project Overview](#project-overview)

[Data Sources](#data-sources)

[Tools Used](#tools-used)

[Data Cleaning and Preparations](#data-cleaning-and-preparations)

[Exploratory Data Analysis](#exploratory-data-analysis)

[Data Analysis](#data-analysis)

[Table](#table)

[Data Visualization](#data-visualization)

### Project Overview: 
----
 This copier sales report is to have a deep insight into the sales performance for the period of two years, that is 2014 and 2015, considering the model, Region and Line Of Business. This parameters from the data received helped in gathering enough fact to tell a compelling story.

### Data Sources:
----
 The data source used in the report is data sales, csv file, that was gotten freely from kaggle [Download Here](https://kaggle.com)

### Tools Used: 
----
- Microsoft Excel for Data Cleaning, Analysis and Visualization [Download Here](https://microsoft.com)
- GitHub for portfolio Building [Download Here](https://github.com)

### Data Cleaning and Preparations:
----
We started the Data cleaning and preparation as follows:
- Data loading and inspection.
- Data cleaning and formatting.

### Exploratory Data Analysis:
----
 Exploratory Data Analysis addresses the fact about the data such as:
 - Which Model are top in Sales.
 - Which Region has the overall Sales trend.
 - What Month/Year recorded the highest Sales.
 - What Line Of Business has the highest unit sold

### Data Analysis:
----
- where we include some basic lines of code or queries or even some of the DAX expressions used during your analysis;
-  ```Microsoft Excel
   IF (J2 <= 20, "Low", IF(J2 <= 50, "Medium", "High"))
   ```
### Table
----
   |Units Sold|Category|
   |----------|--------|
   |1 - 2|Low|
   |21 - 50|Medium|
   |> 50|High|

### Data Visualization:
----
    
![Sales by Region](https://github.com/user-attachments/assets/b6f119f2-dae3-467b-be5c-5a85fd3a1e24)




![Sales by Model](https://github.com/user-attachments/assets/21910498-7e9c-4765-91fc-4bc31331dcba)



 ![Unit Sold by Region](https://github.com/user-attachments/assets/ce56a2ec-4ccd-4be1-9cef-066670371751)


![Uint Sold by Line Of Business](https://github.com/user-attachments/assets/e6b972ec-0dc0-448c-922f-0c040e593dfd)


![Sales by Month](https://github.com/user-attachments/assets/0ef79a0a-e778-44cf-9e21-9e089de293c3)



![Copier sales report](https://github.com/user-attachments/assets/5c0014db-ed1f-4e30-ac4d-33afa757ebb1)


![Thank You](https://github.com/user-attachments/assets/b67e04e7-dfd8-4e95-9f92-0870ca24209e)









### Project Title: Sales Data Analysis


![20241102_122023](https://github.com/user-attachments/assets/379002bf-d37b-477e-afc7-541b30ab4712)


[Introduction](#introduction)

[Data Source](#data-source1)

[Tools Used](#tools-used1)

[Data Cleaning and Preparations](#data-cleaning-and-preparations1)

[Problem Statement](#problem-statement)

[Data Analysis](#data-analysis1)

[Table](#table1)

[Conclusions And Recommendations](#conclusions-and-recommendations)

[Data Visualization](#data-visualization1)

### Introduction: 
---
This is a project work given to me after completing my Ten weeks Data Analysis bootcamp with Incubator Hub under the Umbrella of Lady’s In Tech Africa (LITA). It’s to analysis sales of Product based on top performing product, Months and Regional breakdown for the period of two years. 

### Data Source1:
---
The Data source used in this project is Sales Data, an Excel file containing just a table with fifty thousand rows and seven columns that was sent across the bootcamp by my Data Analysis Instructor (Mr. Temidayo TeeDee). 😄

### Tools Used1:
---
- Microsoft Excel to calculate the Revenue column, Pivot table to Analyze the data.
- SQL to query and manipulate the data.
- Power BI to visualize.
- GitHub for portfolio building.

### Data Cleaning and Preparations1: 
---
I started the data cleaning and preparation as follows:
- Data loading and inspection on Microsoft Excel 
- Multiplying Quantity by Unit Price, Revenue was calculated. 
- Data loading and inspection on SQL
- Querying and manipulation of the table
- Data loading and inspection on Power BI.

### Problem Statement:
---
- The total revenue for each product category.
- Number of sales transactions in each Region.
- Highest selling product by total revenue.
- Monthly total revenue.
- Top 5 customers with total purchase amount.
- Total revenue by product, Region and Month.

### Data Analysis1:
---
Some lines of codes were used to carry out this analysis and they are shown below:

 ```Microsoft Excel
 = [Quantity] * [UnitPrice]
```

Retrieve the total sales for each product category

 ```SQL
 select Product, Sum(Revenue) Total_Sales
  from capstone_salesdata
  Group By Product
  Order By Total_Sales Desc
```

Find the number of sales transactions in each region 

  ```SQL
  select Region, sum(Quantity) Sales_Transaction
  from capstone_salesdata
  Group By Region
  order by Sales_Transaction desc
```

Find the highest selling product by total sales value

  ```SQL
  select Product, SUM(Revenue) Total_Sales
  from Capstone_SalesData
  Group by Product
  Order by Total_Sales Desc
```



### Table1
---

![Data Table](https://github.com/user-attachments/assets/5a43fde7-a041-4770-bcc6-fbe782d1ba19)


### Conclusions And Recommendations:
---
- The Total Revenue was 10,587,500.
- The Total number of Customer was 50,000.
- The Month of February 2024, recorded the highest Revenue which was 1,500,000 and April 2023 has the lowest Revenue month with a total of 37,500.
- Southern Region recorded the highest revenue of about 4,675,000, followed by Eastern Region with a total of 2,450,000, then the Northern Region recorded a total Revenue of 1,950,000 and lastly the Western Region with a total revenue of 1,512,500.
- The Revenue generated by Product from the highest to the lowest:
Shoes = 3,087,500
Shirt = 2,450,000
Hat = 1,587,500
Gloves = 1,500,000
Jacket = 1,050,000
Socks = 912,500
- Numbers of customers per region are equal which is 12,500 for the four Regions.
- Shoes and hats recorded the highest number of customers with a total number of 10,000 and all other products has the same number of customers which is 7,500.
  
### Data Visualization1:
---


![Highest selling prod](https://github.com/user-attachments/assets/033375a0-9011-498b-ade1-9ce83b927f9a)


![Monthly sales for curr  Year](https://github.com/user-attachments/assets/25a500fc-9561-4fbf-8aae-2cd6e25ffa8f)



![top 5 customers](https://github.com/user-attachments/assets/402d819b-dfa3-4be5-906d-ffb88c28b8f9)



![Salaes per Product](https://github.com/user-attachments/assets/d83471c8-9fc7-4862-bbb5-096689934e15)



![Sale tran  Per Reg](https://github.com/user-attachments/assets/8fee085f-bed2-4e1b-a975-efa003f70a5a)



![Pivot Table SD](https://github.com/user-attachments/assets/d621727d-fb4c-414b-bec2-5e4970959dee)




![Power BI SD Dashboard](https://github.com/user-attachments/assets/dbcd9af0-953b-4de4-842f-c7380a94638b)





![20241103_062106](https://github.com/user-attachments/assets/21972ab0-1df7-42b3-a9ea-5f9d3b898a41)







### Project Title: Customers Subscription Analysis



![20241102_122159](https://github.com/user-attachments/assets/286ff9ca-e565-4ded-b394-68fd4e733bad)

[Project Overview](#project-overview2)

[Data Source](#data-source2)

[Tools Used](#tools-used2)

[Data Cleaning and Preparations](#data-cleaning-and-preparations2)

[Problem Statement](#problem-statement2)

[Data Analysis](#data-analysis2)

[Table](#table2)

[Conclusions And Recommendations](#conclusions-and-recommendations2)

[Data Visualization](#data-visualization2)


### Project Overview2: 
---
This is a project work given to me after completing my Ten weeks Data Analysis bootcamp with Incubator Hub under the Umbrella of Lady’s In Tech Africa (LITA). Its to analysis customer’s subscription trend, based on subscription type, Region and customers who have cancelled their subscriptions and the active ones for a period of two years. 

### Data Source2:
---
The Data source used In this project is Customer Data, an Excel file containing just a table with seventy-five thousand rows and eight columns that was sent across the bootcamp by my Data Analysis Instructor (Mr. Temidayo TeeDee).

### Tools Used2:
---
- Microsoft Excel to calculate subscription duration column, Pivot table to analyze the data.
- SQL to query and manipulate the data.
- Power BI used to add a conditional column and then visualization.
- GitHub for portfolio building.

### Data Cleaning And Preparations2: 
---
I started the data cleaning and preparation as follows:
- Data loading and inspection on Microsoft Excel 
- Using the difference between subscription end and subscription start, subscription duration column was calculated. 
- Data loading and inspection on SQL
- Querying and manipulation of the table
- Data loading and inspection and then visualization on Power BI
- Conditional column was created for canceled count and measures were created.

### Problem Statement2:
---
- The total number of customers from each Region.
- Find the most popular subscription type by number of customers 
- Find the subscription duration for each customer and the average subscription duration for all customer.
- Find the total revenue by subscription type 
- Top 3 Regions by subscription cancellation.

### Data Analysis2:
---

  = [SubscrptionEnd] – [SubscriptionStart]
 
  If Canceled = "TRUE", then output 1
  Else 0

 ### Table2
---

![Customer Table](https://github.com/user-attachments/assets/2b7caca2-8063-4623-ac51-fba436478474)


### Conclusions And Recommendations2:
---
- The Total Revenue was 149, 819,686
- The Average subscription duration was 365 days 
- The total number of customers was 75,000 and number of canceled subscriptions was 33,750 while active subscribers were 41,250
- There was no canceled subscription in the Eastern Region, while other Regions all have the same amount of canceled subscription which is 11,250.
- South Region has the highest revenue of about 37,580,782, followed by West with a total of 37,482.120, then the East with a total number of 37,387,894 and lastly the Northern Region with a total of 37,368,899.
- The Basic subscription type recorded the highest in terms of Revenue which was 74,756,784, followed by Premium with a total Revenue of 37,580,782 and the last which is Standard with a total of 37,482,120.
- Numbers of customers per region are equal which is 18,750 for the four Regions.
- Basic subscription type recorded the highest number of customers with a total number of 37,500 and both Premium and Standard has the same number of subscribed customers which is 18,750.

### Data Visualization2:
---

![Rev  By sub Type](https://github.com/user-attachments/assets/880dfd29-be60-4a2b-8bda-43381d43beea)

![Highest sub Type, DC, sql](https://github.com/user-attachments/assets/7f807225-7d94-480f-8257-027d042612cc)


![No  of Active   Cancel](https://github.com/user-attachments/assets/a07ed572-381f-418a-a33a-134eb76b62bd)


![No  of customers, CD, SQL](https://github.com/user-attachments/assets/ca988d1e-f4ac-4a0d-94bc-987cc99c4402)


![Avg Sub  Duration, CD, SQL](https://github.com/user-attachments/assets/5da7e822-8962-47fc-993e-573dd7b3dd57)


![Excel Pivot](https://github.com/user-attachments/assets/b9e44e9b-1574-4449-8c55-e97a9d8e195b)


![Power BI Dashboard](https://github.com/user-attachments/assets/8ba570e3-2c1d-41f2-9650-bb713e896a2e)


![20241103_062840](https://github.com/user-attachments/assets/0f86815d-fe3b-45f9-9609-3ef236f402be)
