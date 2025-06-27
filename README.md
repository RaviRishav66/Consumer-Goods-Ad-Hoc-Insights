# Consumer-Goods-Ad-Hoc-Insights

## Project Overview and Problem Statement

Atliq Hardware (imaginary company) is one of the leading computer hardware producers in India and well expanded in other countries too, specializes in selling computers and accessories.

The management noticed that they did not get enough insights to make quick and smart data-informed decisions. 
However, Tony Sharma (Data Analytics Director ) wants to expand their data analytics team by adding several junior data analysts. So he decided to conduct a SQL challenge which will help him understand both tech and soft skills

Now the company wants insights for 10 ad hoc / business requests.

This project is part of the data analyt
ics boot camp at codebasics.

## Data Structure/ Data Modeling and Tools

The 'gdb023' (atliq_hardware_db) database was provided to me to work on and it includes six main tables:

1. dim_customer: contains customer-related data
1. dim_product: contains product-related data
1. fact_gross_price: contains gross price information for each product
1. fact_manufacturing_cost: contains the cost incurred in the production of each product
1. fact_pre_invoice_deductions: contains pre-invoice deductions information for each product
1. fact_sales_monthly: contains monthly sales data for each product.

Here is the Data Model that I have created in Power BI for the Visualization part -

![32](https://github.com/user-attachments/assets/a848ec57-3a9f-4d98-9360-11e8b2f2875e)



**Tools used -** 

* I used My SQL to answer the questions 
* Power BI for visualization

## 10 Ad-Hoc Requests and Outputs:

### 1. Provide the list of markets in which customer "Atliq Exclusive" operates its business in the APAC region.

![2](https://github.com/user-attachments/assets/30e16a6e-1304-4724-929a-81ce8791986d)


### 2. What is the percentage of unique product increase in 2021 vs. 2020? The final output contains these fields, unique_products_2020, unique_products_2021, percentage_chg

![5](https://github.com/user-attachments/assets/c53ea2e4-974f-4ebb-a94a-d9c56290edc5)


### 3. Provide a report with all the unique product counts for each segment and sort them in descending order of product counts. The final output contains 2 fields, segment product_count

![8](https://github.com/user-attachments/assets/92734880-d28d-4166-b230-6ed05f7dcec1)



### 4. Follow-up: Which segment had the most increase in unique products in 2021 vs 2020? The final output contains these fields, segment product_count_2020, product_count_2021, difference

![10](https://github.com/user-attachments/assets/7a8747fc-9599-45c5-9ca6-4632cbc165b2)



### 5. Get the products that have the highest and lowest manufacturing costs. The final output should contain these fields, product_code, product, manufacturing_cost


![14](https://github.com/user-attachments/assets/fae29583-a563-4e01-ae46-3ce37ff5ffde)



### 6. Generate a report that contains the top 5 customers who received an average high pre_invoice_discount_pct for the fiscal year 2021 and in the Indian market. The final output contains these fields, customer_code, customer, average_discount_percentage

![16](https://github.com/user-attachments/assets/7a6565d8-5f16-4ac9-978a-4558d7159714)



### 7. Get the complete report of the Gross sales amount for the customer “Atliq Exclusive” for each month. This analysis helps to get an idea of low and high-performing months and make strategic decisions. The final report contains these columns: Month, Year, Gross sales Amount

![19](https://github.com/user-attachments/assets/3ee34ade-26dc-4290-b5f3-d7a022ac3551)



### 8. In which quarter of 2020, got the maximum total_sold_quantity? The final output contains these fields sorted by the total_sold_quantity, --> Quarter, total_sold_quantity

![22](https://github.com/user-attachments/assets/b067d4b2-3faa-4914-811c-4c0433f72e68)



### 9. Which channel helped to bring more gross sales in the fiscal year 2021 and the percentage of contribution? The final output contains these fields --> channel, gross_sales_mln, percentage


![24](https://github.com/user-attachments/assets/adcbd935-df0c-475a-9c2c-03ed42fa8eaf)



### 10. Get the Top 3 products in each division that have a high total_sold_quantity in the fiscal_year 2021? The final output contains these fields, division, product_code

![27](https://github.com/user-attachments/assets/efc2e58d-a196-40ff-9224-ed922e96df69)


============================================================================================
