# Forggith Pharmaceuticals Business Analysis

## Introduction
Forggith Pharmaceuticals (Forggith) is a Pharmaceutical Manufacturing company based in Germany. As a Manufacturing company, they produce medical drugs which get to the consumers through their Distributors.

Forggith provided a template for their distributors to capture records of their sales which are then sent to Forggith on a monthly basis. This data is then used for reporting and analysis by Forggith to achieve their goals Sales and Marketing objectives through tracking and monitoring of KPIs.

In their efforts to maximise growth, Forggith works with a team of Sales and Marketing pros who ensure retailers are able to get their products through the distributors. That is, Forggith does not sell directly to retailers or end-users, they sell to Distributors. But they maintain interaction with retailers, through their Sales and Marketing pros.

###[View Report](https://app.powerbi.com/view?r=eyJrIjoiMjVlNzFiZDUtMjQ3NC00YTA1LTk4ZDAtY2EzZDZiYjU2ZGQzIiwidCI6IjBkNDE2ZjQ5LTE2MzItNDcwMS1iN2Q4LWIzMjY1OTk3YmY5MyJ9)
## Data Source
The data was sourced from [Foresight BI and Analytics Internship](https://training.foresightbi.com.ng/courses/take/power-bi-developer-internship/texts/45012192-introduction-to-the-program)

Also found [HERE](https://github.com/Ojochonu-Godian/Forggith_Pharma/blob/main/PharmDataset-230517-152700(1).xlsx)

## Understanding the Dataset
The dataset consist of Sales Data and Target Data. The sales data contains sub-datasets namely; Sales Data (2022 - 2025), Products, Location, Channel, Sub-channel, and Employees.
## Data Modelling
By utilizing Microsoft Power BI's modelling capability, a star-schema data model was implemenented in order to optimize interactions between the different tables. A calender table for time series analysis was also created and connected to the sales data as shown below.

![DataModel](https://github.com/Ojochonu-Godian/Forggith_Pharma/assets/104824781/9bcfb132-613d-4c4a-895c-bd40e915a06f)

## Data Transformation and Key Performance Indicators

***The Key Performance Indicators for Sales Performance are;***
* Total  Revenue
* Total Revenue Year To Date (YTD)
* Total Revenue Previous Year YTD
* Total Revenue Same Period Last Year(SPLY)
* Total Target
* Total TargetYTD
* Actual Revenue Performance YTD vs Target YTD
* Revenue Month on Month Percentage Change
* Revenue Distribution by Location
* Revenue by Channel
* Revenue by Product Class

***The Key Performance Indicators for Marketing Performance Performance are;***
* Revenue Achieved vs Revenue Target
* Volume Achieved vs Volume Target
* Actual Revenue by Sales Representative
* Target Revenue Achievement% by Sales Representative
* Actual Volume by Sales Representative
* Target Volume Achievement by Sales Representative
* Actual Revenue Achievement by Sales Team
* Revenue and Volume Achievement by Product.



## Exploratory Data Analysis and Data Visualization
Displayed in the dashboards are visual representations of the key performance indicators.
![Sales Performance Overview](https://github.com/Ojochonu-Godian/Forggith_Pharma/assets/104824781/2b5399f4-3669-4cda-bc53-b9be2b5b893a)


![forggith 5](https://github.com/Ojochonu-Godian/Forggith_Pharma/assets/104824781/55de1589-132a-4905-9a6b-18fa1bfb066d)

In this project I would like to give data driven answers to the following business questions;
1. Which customer segment generates the highest sales revenue?
3. How does sales performance vary across different geographical regions?
4. What is the average quantity of products ordered per customer?
5. Which city has the highest number of orders?
6. What is the distribution of sales by product category?
7. How does the discount rate affect sales revenue?
8. Which sales representative has the highest sales performance?
9. What is the average profit margin for each product category?
10. How does the shipping mode impact the delivery time?
11. Which product sub-category has the highest sales volume?
12. What is the trend in sales revenue over time?
13. Are there any correlations between sales performance and customer location?
14. How does the sales performance of each sales team compare?
15. What are the top-selling products in each product category?
16. How does the profit margin vary for different shipping modes?
17. Is there any seasonality in the ordering patterns?
18. How does the discount rate affect the quantity of products ordered?
19. What is the average order value per customer segment?
20. Are there any outliers in sales performance that require further investigation?

### What is the total sales amount for each customer?

