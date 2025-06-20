# ADVENTURE_WORKS ANALYSIS
## BY OFOLEBE CYNDI
---
![image alt](https://github.com/Cyndi-24/Adventure-works-Project/blob/main/Adventure%20works%20BI%20PROJECT/adventure_works_images/Adventure_works_logo.png)
---

# INTRODUCTION
---
I took up this project to challenge myself,further improve my analytics skills and gain more experience in the use of PowerBI.

---

# PROBLEM STATEMENT
---
 Adventure Works represents a cycling company with data on products,sales,customers and employees. Despite the growing customer base there seems to be a decrease in revenue generated between the years 2015 and 2017.With the help of data analysis we will help the mangement team  try to understand the customers spending patterns and the reason for the decrease in revenue thus implementing strategies to improve performance
 Data was collected on the customers,demographics,sales,products purchased,period of purchases,product category,date of purchase,country etc. Using the data provided I will be answering the following questions along with the use of KPI's which further summarize the data set making it easier to come up with and implement strategies.
 * Which gender had the most patonage?
 * Which customers by educational level patronised the most?
 * Based on income segment which customers patronised the most?
 * Which country had the most customers?
 * What are the top 5 products by revenue?
 * Who are the top 10 customers by revenue?
 * What was the revenue generated by each product category?
 * What  was the monthly revenue?
 * What revenue was generated by each country?

---
# DATA SOURCING
 This dataset was gotten from Kaggle.com, a website which offers a vast repository of datasets which can be used for personal projects and competitions for data enthusiasts and professionals
 
 ---
 
 # SKILLS DEMONSTRATED
 ---
 * Data Importation;
   The dataset was saved in csv format and imported into PowerBI
 ---
 * Data Transformation;
  After importing the data to PowerBI, I did a lot of transformation using PowerBI query editor which involved removing unnecessary 
  columns and rows,removing duplicates,adding new columns and rows where necessary,formating the data types for each column,merging the 
  date tables using append query and creating a calendar date table using DAX measures to make the analysis easier.
---
 * Data Modelling
   I have nine tables;
   * AdventureWorks_Customers
   * AdventureWorks_Product_category
   * AdventureWorks_Product_Subcategory
   * AdventureWorks_Product
   * AdventureWorks_Returns
   * AdventureWorks_Sales_2015
   * AdventureWorks_Sales_2016
   * AdventureWorks_Sales_2017
   * AdventureWorks_Territory
     
   Loading the data set created an automatic data model but adjustments were made which include;
   * Adding a calendar table to the model
   * Using DAX for cross-filtering instead of setting cross filtering direction to both as this allows for more dynamic filtering
   * With the help of dax measures I was able to analyze the dataset,calculate ,add aggregated columns etc
  
     The image below shows the adjusted model view
 --- 
  ![image alt](https://github.com/Cyndi-24/Adventure-works-Project/blob/main/Adventure%20works%20BI%20PROJECT/adventure_works_images/model_view.png)
---   
# ANALYSYS AND VISUALIZATION
---
  This report contains two dashboard;customer and sales
  
---

 ![image alt](https://github.com/Cyndi-24/Adventure-works-Project/blob/main/Adventure%20works%20BI%20PROJECT/adventure_works_images/customer_dashboard_2015.png)

---
 ![image alt](https://github.com/Cyndi-24/Adventure-works-Project/blob/main/Adventure%20works%20BI%20PROJECT/adventure_works_images/sales_dashboard_2015.png)     

---
 KPI's for customer report 2015
---

![image alt](https://github.com/Cyndi-24/Adventure-works-Project/blob/main/Adventure%20works%20BI%20PROJECT/adventure_works_images/Average_Income_%20customer_2015.png)
![image alt](https://github.com/Cyndi-24/Adventure-works-Project/blob/main/Adventure%20works%20BI%20PROJECT/adventure_works_images/total_customers_kpi_2015.png)

From 2015 t0 2016 there was an in increase in total customers by 247% and from 2016 to 2017 there was an incrsase by 15%

---
Which gender had the most patronage?
---
![image alt](https://github.com/Cyndi-24/Adventure-works-Project/blob/main/Adventure%20works%20BI%20PROJECT/adventure_works_images/customer_by_gender_2015.png)

 The females patronised the most
    
---
Which customers by educational level patronised the most?
---
![image alt](https://github.com/Cyndi-24/Adventure-works-Project/blob/main/Adventure%20works%20BI%20PROJECT/adventure_works_images/customer_edu_level_2015.png)

 Bachelors 

---
Which customer by income segment patronised the most?
---
![image alt](https://github.com/Cyndi-24/Adventure-works-Project/blob/main/Adventure%20works%20BI%20PROJECT/adventure_works_images/customer_income_sgt_2015.png)

Average Income Earners patronised more than other income segments

---
Which country had the most customers?
---
![image alt](https://github.com/Cyndi-24/Adventure-works-Project/blob/main/Adventure%20works%20BI%20PROJECT/adventure_works_images/customer_by_country_2015.png)

Europe had the most customers

---
What are the top 5 products by revenue?
---
![image alt](https://github.com/Cyndi-24/Adventure-works-Project/blob/main/Adventure%20works%20BI%20PROJECT/adventure_works_images/product_by_revenue-sales2015.png)

 Road-150,Red 48 genarated the most revenue in 2015

---
Sales Report KPI's 2015
---
![image alt](https://github.com/Cyndi-24/Adventure-works-Project/blob/main/Adventure%20works%20BI%20PROJECT/adventure_works_images/sales_kpi_2015.png)
---
Sales Report KPI's 2016
---
![image alt](https://github.com/Cyndi-24/Adventure-works-Project/blob/main/Adventure%20works%20BI%20PROJECT/adventure_works_images/sales_kpi_2016.png)
---
Sales Report KPI's 2017
---
![image alt](https://github.com/Cyndi-24/Adventure-works-Project/blob/main/Adventure%20works%20BI%20PROJECT/adventure_works_images/sales_kpi_2017.png)

Comparing the KPI's across the three years there was an increase in the total orders across the years by 307% in 2016 and 11% in 2017,but there was a decrease in revenue yearly as the total orders decrease thus the target of 5million was only met in 2015

---
What was the revenue generated by each product category?
---
![image alt](https://github.com/Cyndi-24/Adventure-works-Project/blob/main/Adventure%20works%20BI%20PROJECT/adventure_works_images/product_cat_by_rev_sales2015.png)

Bikes generated the most revenue across the three years but generated the most in 2015 with 6million but there was a  decline to about  4 million in 2016 and to 1.4 million in 2017.

---
Who are the top customers by revenue?
---
![image alt](https://github.com/Cyndi-24/Adventure-works-Project/blob/main/Adventure%20works%20BI%20PROJECT/adventure_works_images/customers_by_revenue_sales2015.png)

---
What was the revenue generated monthly?
---
![image alt](https://github.com/Cyndi-24/Adventure-works-Project/blob/main/Adventure%20works%20BI%20PROJECT/adventure_works_images/monthly_trend_sales2015.png)

Over the three year period,the revenue grows gradually increases and hits its peak around June and steadily declines down the year.

---
Which country generated the most revenue?
---
![image alt](https://github.com/Cyndi-24/Adventure-works-Project/blob/main/Adventure%20works%20BI%20PROJECT/adventure_works_images/revenue_by_country_2015.png)

Australia generated the most revenue

---
RECOMMENDATION AND CONCLUSION
---
* Following the  monthly trend,sales gradually increases as the year begins and peaks up at June while gradually decreasing afterwards,more investigation needs to be done by the sales team to find out why in order to improve sales during the months of low sales and how to optimize and further boost revenue during May/June.
* From product category,bikes generated the most revenue across the three years especially Road-150,Red 48 in 2015,thus there is need to constantly ensure the bikes in demand are always stocked up and readily available for purchase and delivery to the customers.
* Europe had the most customers but it generated lesser revenue compared to Australia which generated the most revenue with lesser customers.This should be looked into by the marketing team in order promote advertisement of the company's product in thise areas.
* Finally, since majority of the customers are average income earners the prices of the products should be looked into to ensure that the target market can afford the products. 
