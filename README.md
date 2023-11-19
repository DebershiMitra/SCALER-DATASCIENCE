# SCALER-DATASCIENCE
 Unlocking the Secrets of Retail Success: My End-to-End Data Project at Target 🛒
🎯 Unlocking the Secrets of Retail Success: My End-to-End Data Project at Target 🛒🎯 Unlocking the Secrets of Retail Success: My End-to-End Data Project at Target 🛒
Jun 2023 - Jul 2023Jun 2023 - Jul 2023

Associated with ScalerAssociated with Scaler
In this exciting endeavor, I delved deep into the world of US-based grocery retail store, focusing on the renowned industry leader, Target. 🎯

✨ Project Objective: My goal was to analyze various aspects of Target's operations and uncover valuable insights to drive growth, optimize performance, and enhance the overall customer experience. 📈

💡 Methodology: Leveraging my data analysis expertise, I embarked on an end-to-end project, encompassing data collection, cleansing, and analysis. Using SQL, I extracted and transformed vast amounts of data from given data, enabling a comprehensive understanding of their retail landscape. 🔍

🔎 Data Exploration: I meticulously examined diverse facets of Target's grocery operations, such as sales trends, customer behavior, inventory management, and marketing initiatives. By applying advanced SQL queries and techniques, I discovered hidden patterns and correlations within the data. 📊

🚀 Key Insights Unveiled: Throughout this project, I uncovered actionable insights that could revolutionize Target's strategies. From identifying optimal pricing strategies for specific products to optimizing supply chain operations, the data-driven findings hold immense potential for enhancing efficiency, profitability, and customer satisfaction. 

🤝 Acknowledgments: I would like to express my gratitude to the amazing team at Scaler for providing invaluable support and access to the data necessary to complete this project successfully. 🙏

🌟 Let's Connect! If you're interested in learning more about my end-to-end data project at Target or want to discuss how data-driven insights can revolutionize the retail industry, feel free to reach out. I look forward to engaging with like-minded professionals! 🤝

Remember, this description is just a starting point. Feel free to personalize and expand upon it to align with your specific project and experiences. Good luck!In this exciting endeavor, I delved deep into the world of US-based grocery retail store, focusing on the renowned industry leader, Target. 🎯 ✨ Project Objective: My goal was to analyze various aspects of Target's operations and uncover valuable insights to drive growth, optimize performance, and enhance the overall customer experience. 📈 💡 Methodology: Leveraging my data analysis expertise, I embarked on an end-to-end project, encompassing data collection, cleansing, and analysis. Using SQL, I extracted and transformed vast amounts of data from given data, enabling a comprehensive understanding of their retail landscape. 🔍 🔎 Data Exploration: I meticulously examined diverse facets of Target's grocery operations, such as sales trends, customer behavior, inventory management, and marketing initiatives. By applying advanced SQL queries and techniques, I discovered hidden patterns and correlations within the data. 📊 🚀 Key Insights Unveiled: Throughout this project, I uncovered actionable insights that could revolutionize Target's strategies. From identifying optimal pricing strategies for specific products to optimizing supply chain operations, the data-driven findings hold immense potential for enhancing efficiency, profitability, and customer satisfaction. 🤝 Acknowledgments: I would like to express my gratitude to the amazing team at Scaler for providing invaluable support and access to the data necessary to complete this project successfully. 🙏 🌟 Let's Connect! If you're interested in learning more about my end-to-end data project at Target or want to discuss how data-driven insights can revolutionize the retail industry, feel free to reach out. I look forward to engaging with like-minded professionals! 🤝 Remember, this description is just a starting point. Feel free to personalize and expand upon it to align with your specific project and experiences. Good luck!
Skills: Databases · Data Analytics · Google BigQuery · MySQL · Microsoft SQL Server



About Walmart
Walmart is an American multinational retail corporation that operates a chain of supercenters, discount departmental stores, and grocery stores from the United States. Walmart has more than 100 million customers worldwide.
Business Problem
The Management team at Walmart Inc. wants to analyze the customer purchase behavior (specif- ically, purchase amount) against the customer’s gender and the various other factors to help the business make better decisions. They want to understand if the spending habits differ between male and female customers: Do women spend more on Black Friday than men? (Assume 50 million customers are male and 50 million are female).
Dataset:
The company collected the transactional data of customers who purchased products from the Walmart Stores during Black Friday. The dataset has the following features:
User_ID: User ID Product_ID: Product ID Gender: Sex of User Age: Age in bins.
Occupation: Occupation(Masked) City_Category: Category of the City (A,B,C).
StayInCurrentCityYears: Number of years stay in current city ProductCategory: Product Category (Masked).
Purchase: Purchase Amount.

1.
Q Defining Problem Statement and Analyzing basic metrics (10 Points) Ans . If spending habits differ between
male and female customers.
Q. Observations on shape of data, Ans. (550068 ,10) Total 5,50,068 products bought on Black Friday.
Q. Data types of all the attributes, Ans
0 User_ID 550068 non-null int64 1 Product_ID 550068 non-null object 2 Gender 550068 non-null object 3 Age
550068 non-null object 4 Occupation 550068 non-null int64 5 City_Category 550068 non-null object 6
Stay_In_Current_City_Years 550068 non-null object 7 Marital_Status 550068 non-null int64 8 Product_Category
550068 non-null int64 9 Purchase 550068 non-null int64
Q.Conversion of categorical attributes to 'category' (If required), statistical summary : Ans. Coverted
Occupation, Product Category and Marital Status int64 to Object.
Q. Value counts and unique attributes Ans 0 User_ID 5891 unique users. 1 Product_ID 3631 unique products. 2
Gender 4423 Males, 1666 Females 3 Age Total 7 age bins, 26-35(40%),36-45(20%),18-25(18%) 4 Occupation 20
unique product categories 5 City_Category A(27%),B(42%),C(31%) 6 Stay_In_Current_City_Years 0(14%) 1(35%)
,2(19%),3 (17%) or 4+(15%) 7 Marital_Status 0(59%) or 1(41%) 8 Product_Category 20 unique product categories
9 Purchase.

2.
Q Missing Value & Outlier Detection Ans There are no missing value in dataset. There are outlier present for the
varaible purchase and total spend per user when purchase aggregated per user.
3.
Q Business Insights based on Non- Graphical and Visual Analysis (10 Points) Final Insights
1. Total 5891 unique customers and 3631 unique products.
2. Most sold product is P00265242, sold 1880 times. Increase the inventory of these products.
3. There are no null values in the dataset.
4. Cheapest product cost 12 , mean cost of a product is 9263.96, and max cost of a product is 23961.
5. Total 5,50,068 items sold.
6. Total 20 unique product categories and 20 differnent types of occupations. 7.Product Category 5,1,8 are sold
the most. They should be kept in high visibility area of Walmart stores.
7. Mean,Median purchase amount for males is = 9438 and 8098 respectively.
8. Mean,Median purchase amount for females is = 8735 and 7914 respectively.
9. Clearly men on average are spending per transaction more then women. This could be due to number of
reasons.
10. Men prefer expensive products.
11. Maybe, men are paid more than women hence spend more.
12. Target men with campaigns and advertisement of products with high price.
13. Women make more economical choices while buying products then men. #Value count Insight
14. 75% transactions on Black friday are done by males.
15. 4225 (72%) people are Male while 1666 (28%) customers are Female.
16. 3417 (58%) customers are single while 2474 (42%) are married.
17. Most no (42%) transactions are done in City B.
18. 59% transactions are done by single people.
19. Most no (40%) transactions are done BY people in age group 26-35.
20. 35% transactions are done by people who have lived for one year in the city.
21. People with occupation 4(13%),0(13%),7(13%) transact the most on Black friday.
22. Product category 5 (27%),1 (26%),8 (21%) are sold the most during Black Friday. # Product insight
23. No of unique products sold are == 3631 25.No of unique products bought by Males are == 3588 26.No of
unique products bought by Females are == 3367
Product Category Insight
1. Product Category 1 is most bought category by Male while 5 is the most bought category by females.
#Insight on total_spend and Total products per user on Black friday
2. Total spend follows a log normal distribution.
3. There are outliers present in the dataset for the total spend by each customer during black friday sales.
4. Median value for total spend on black friday per user for male and female is 5,23,983 and 5,19,347
respectively.
5. Median value for total products bought per user for male and female is 10 and 9 respectively.
Insights on Categorical Variable per user statistics
1. 4225 (72%) people are Male while 1666 (28%) customers are Female.
2. 3417 (58%) customers are unmarried while 2474 (42%) are married.
3. Majoity of customers fall in 26-25 age group followed by 36-45 group. Walmart Can include more products
for this age group. Target more advertisement towards this age group. Least no of 35. customers in age
group 0-17 and 46 and above. Can take meausres to improve their purchase behaviour by introducing new
products for this age group.
4. Majority customers belong to C city category and least to city A. City C customers should be of prime focus
as they generate most of the revenue. Send discount offers to the people who have been staying less than a
year in the city to increase their sales.
4.
Q1. Are women spending more money per transaction than men? Why or Why not? Ans1. Mean,Median
purchase amount for males is = 9438 and 8098 respectively. Mean,Median purchase amount for females is =
8735 and 7914 respectively.
Clearly men on average are spending per transaction more then women. This could be due to number of
reasons.
1. Men prefer expensive products.
2. Maybe, men are paid more than women hence spend more.
3. Men are targetted with campaigns and advertisement of products with high price.
4. Women make more sensible/conservative choices while buying products.
Q2. Confidence intervals and distribution of the mean of the expenses by female and male customers (10 Points)
Ans2.
Approximate population mean for total spend per Male is 925479 Approximate population mean for total spend
per Female is 711445
95 CI for Average Spending by a male customer on black friday is (876429,978355) 95 CI for Average Spending by
a female customer on black friday is (681338,743533)
Q3. Are confidence intervals of average male and female spending overlapping? How can Walmart leverage this
conclusion to make changes or improvements?
1. Confidence interval of average male and female customer spendings are not overlapping.
2. We can conclude that on average males customer spend more than a female customer.
3. Male customers are more likely to buy expensive products in comparison to female customers.
4. Walmart should target ads with expensive products to male customers. Female customers should be
targetted with economical products.
Q4. Results when the same activity is performed for Married vs Unmarried (10 Points)
1. Sample mean's mean for total spend for a married and single customer is 843860 and 879924.
2. 95 CI for Average Spending by a marital customer and single customer on black friday is (800084 ,889695 )
and (833226,929482) respectively.
3. Single customers have higher average mean spend then married customers. 95 Confidence interval is also in
a higher spend range for single customers then married customers.
4. There is a lot of overlap b/w avg spend distribution for married and single customers with single customere
lying on thr right tail of distribution i.e
5. There is no significant difference in spending habits of married and single customers based on amount
spend.
Q5. Results when the same activity is performed for Age
1. Customers in 26_25 have highest avg total_Spend value per customer.
2. Customers in age group 55_and_above have lowest mean value for total spend per customer.
Age_Group Mean 95thPercentConfidenceRange 55_and_above 538247 (475280, 597688) 17_and_below
616613 (521137, 718230) 51_55 763122 (675445, 842947) 46_50 788888 (703822, 871824) 18_25 856124 (788832,
925192) 36_45 879474 (813812, 944266) 26_35 991312 (920152, 1064943)
5.
Q5 Final Insights (10 Points) - Illustrate the insights based on exploration and CLT
1. Married and single people on average exhibit not too different purchase behaviour while shopping on black
friday.
2. Male customers spend more on average then female customers while shopping on black friday.
3. People in age group 55 and above and 17 and below on average spend the lowest while shopping on black
friday.
4. People in age group 26-35 and 36-45 on average spend the most while shopping on black friday. 5
P00265242 is the most sold product.
5. Product Category 5,1,8 are sold the most
6. 75% transactions on Black friday are done by males.
7. Most no (42%) transactions are done in City B.
7. Most no (42%) transactions are done in City B.
8. People with occupation 4(13%),0(13%),7(13%) transact the most on Black friday.
9. Product Category 1 is most bought category by Male while 5 is the most bought category by females.
10. As sample size increases there is lot less fluctuation between mean value of sample means.
6.
Q6 Recommendations -->
1. Target Men with campaigns and advertisement of products with high price.
2. Target Women with campaigns and advertisement of products with low price.
3. To increase the sales, keep more products liked by men as they make 75% of total balck friday sales.
4. Keep more stocks in CITY B of products due to most sales coming from CITY B.
5. Target people with Occupation 4,0 and 7 with more personalized advertisements and offers to increase the
sales.
6. Product category 5,1,8 must be kept in high visibility area of Walmart stores to increase the sales.
7. Target male customer with product 1 while female with product 5.
8. P00265242 stocks should be available in excess quantity as the product has highest demand.
9. Send discount offers to the people who have been staying less than a year in the city to increase their sales.
10. Least no of customers in age group 0-17 and 46 and above. Can take meausres to improve their purchase
behaviour by introducing new products for this age group.



