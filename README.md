# Instacart Sales Analysis
---
### by Winnie Ngaji
---
![](images/instacart_logo.png)   
---
# INTRODUCTION
---
Instacart is an American delivery company specialising in grocery delivery and pick-up services, catering to customers in the United States and Canada. The company facilitates seamless access to its services by utilizing both a website and a mobile app. Customers can place orders for groceries from various participating retailers, with the actual shopping conducted by a dedicated personal shopper.

This project aims to conduct a comprehensive analysis of Instacart's business data through SQL queries, aiming to provide actionable insights and answers to key business questions. 

---
# PROJECT OBJECTIVE
I will use the provided dataset to understand Instacart's operational performance, customer preferences, and overall financial success over various periods and product categories. Specifically, I aim to answer the following business questions:

* Q1 What are the top-selling products by revenue, and how much revenue have they generated?
* Q2 Which aisles have the highest sales volume?
* Q3 Which 3 departments generated the most profit in 2019?
* Q4 Which product generated the most profit as of Easter of 2022?
* Q5 Which year did Instacart generate the most profit?
* Q6 What are the top 5 products that generated the most revenue from Christmas 2022 till 2nd of January 2023, and their profits?
* Q7 What time of the day has the highest order volume during the entire COVID period?
* Q8 What is the total revenue generated in Qtr. 2 & 3 of 2016?
* Q9 Which 3 products do people buy at night(2020 - 2022)?
* Q10 What is the total revenue generated from juice products?

---
# TECHNOLOGIES USED
- PostgreSQL
- SQL (advanced queries, joins, aggregations)
- pgAdmin (or mention your SQL IDE)
- Data cleaning and modelling
- Git & GitHub for version control

---
# SKILLS DEMONSTRATED
I used advanced SQL functions to import the dataset into Postgresql and did some analysis to query the database

# DATA MODELLING
I carefully crafted a robust database schema using Postgresql to ensure optimal organization and efficiency. I defined tables, established relationships, and implemented constraints to maintain data integrity.
![](images/creating_tables.png)      

---
### DATA MODEL
![](images/Instacart_data_model.png)     

# DATA ANALYSIS AND VISUALIZATION
I will leverage this database to address and resolve key business challenges that the organization is keen on understanding and solving. By harnessing the power of structured data and relationships established through Postgresql, I aim to provide insightful solutions that contribute to informed decision-making and strategic advancements within the business.

# BUSINESS QUESTIONS
* ### Q1 What are the top-selling products by revenue, and how much revenue have they generated?
### QUERY
![](images/q1_query.png)   
### RESULT
![](images/q1_result.PNG)   
**INSIGHT:::** The top-selling product is Vanilla, Tangerine & Shortbread Ice Cream with a total revenue of $11,184

* ### Q2 Which aisles have the highest sales volume?
### QUERY
![](images/q2_query.png)   
### RESULT
![](images/q2_result.PNG)   
**INSIGHT:::** The "missing" aisle has the highest sales volume, with about 147,708 products sold

* ###  Q3 Which 3 departments generated the most profit in 2019?
### QUERY
![](images/q3_query.png)   
### RESULT
![](images/q3_result.PNG)   
**INSIGHT:::** The top 3 departments were "Personal Care, Snacks and Pantry" and they generated profits of $255,428.70, $244,086.40 and $207,408.90, respectively.

* ### Q4 Which product generated the most profit as of Easter 2022?
### QUERY
![](images/q4_query.png)   
### RESULT
![](images/q4_result.PNG)   
**INSIGHT:::** The product that generated the most profit during the easter period of 2022 was "Chocolate Chip Mini Cookies" with a profit of $79.90.

* ### Q5 Which year did Instacart generate the most profit?
### QUERY
![](images/q5_query.png)   
### RESULT
![](images/q5_result.PNG)   
INSIGHT::: The business generated the most profit of $1,928,129 in 2020

* ### Q6 What are the top 5 products that generated the most revenue from Christmas 2022 till 2nd of January 2023, and their profits?
### QUERY
![](images/q6_query.png)   
### RESULT
![](images/q6_result.PNG)   
**INSIGHT:::** The top 5 revenue-generating products during the Christmas 2022 to January 2, 2023 period were:
Smokestack Mixed Flour, 2% Milk Cheese Singles, Organic Chunky Vegetable Soup, Jammers Grape Juice Drinks and Clinical + Sport Strength Deodorant

* ### Q7 What time of the day has the highest order volume during the entire COVID period?
### QUERY
![](images/q7_query.png)   
### RESULT
![](images/q7_result.PNG)   
**INSIGHT:::** 3 pm had the highest order volume of 14,153

* ## Q8 What is the total revenue generated in Qtr. 2 & 3 of 2016?
### QUERY
![](images/q8_query.png)   
### RESULT
![](images/q8_result.PNG)   
**INSIGHT:::** Qtr. 2 & 3 of 2016 generated a total of $9,555,387 in Revenue

* ## Q9 Which 3 products do people buy at night(2020 - 2022)?
### QUERY
![](images/q9_query.png)          
### RESULT
![](images/q9_result.PNG)      
**INSIGHT:::** The 3 products people bought at night from 2020 - 2022 were Ground Sumatra Deep Roast, Brie & Raspberry Bake & Serve Filled Rolls, and Organic Braggberry

* ## Q10 What is the total revenue generated from juice products?
### QUERY
![](images/q10_query.png)   
### RESULT
![](images/q10_result.PNG)  
**INSIGHT:::** A total of $3,077,822 was generated from juice products

---
# CONCLUSION
This project provided a comprehensive analysis of Instacart's operational data using SQL within a Postgresql environment. Through structured queries and data modelling, I uncovered critical insights into customer behaviour, product performance, and financial trends.

### Key takeaways include:

Top-Selling Product: Vanilla, Tangerine & Shortbread Ice Cream generated the highest revenue ($11,184).

Highest Sales Volume: The "missing" aisle recorded the most product sales (~147,708), indicating a data quality issue.

Top Departments (2019): Personal Care, Snacks, and Pantry led in profits—$255,428.70, $244,086.40, and $207,408.90, respectively.

Holiday Performance: Chocolate Chip Mini Cookies yielded the highest Easter 2022 profit ($79.90); Christmas 2022 sales were also notably high.

Most Profitable Year: 2020 stood out with total profits of $1,928,129, likely influenced by the COVID-19 pandemic.

Peak Order Time: 3 PM had the highest order volume (14,153 orders) during the COVID period.

Nighttime Preferences: Products like Ground Sumatra Deep Roast, Brie & Raspberry Bake & Serve Rolls, and Organic Braggberry were popular between 2020–2022.

Category Highlights: Juice products alone generated $3,077,822 in revenue.

Quarterly Revenue: Q2 and Q3 of 2016 yielded a combined revenue of $9,555,387.

These insights provide valuable guidance for operational optimisation, strategic marketing, and inventory planning.

---
# RECOMMENDATIONS
### Fix Data Quality Gaps

Address the undefined "missing" aisle to ensure accurate categorization and cleaner analytics.

### Promote Top-Selling Products

Boost visibility and marketing for high-revenue items like Vanilla, Tangerine & Shortbread Ice Cream and seasonal bestsellers.

### Leverage Seasonal Trends

Use Easter and Christmas sales patterns to guide future holiday promotions and product positioning.

### Double Down on Profitable Departments

Focus investment and advertising on departments with proven profitability: Personal Care, Snacks, and Pantry.

### Tailor Campaigns for Nighttime Shoppers

Run targeted offers on popular nighttime items to improve engagement during off-peak hours.

### Align Resources with Peak Times

Optimize staffing and logistics around 3 PM, the busiest time of day during the pandemic, to enhance service delivery.




