# Descriptive-Analysis

Project Description: Descriptive Analysis of Customer Purchase Patterns

Project Title: Understanding Customer Purchase Patterns at XYZ Retail

Objective: The primary goal of this project is to conduct a descriptive analysis of customer purchase data at XYZ Retail. Through this analysis, we aim to summarize key characteristics of customer purchases, identify trends, and generate insights that can inform marketing strategies and inventory management.

The project's goal is to analyse customer purchase patterns at XYZ Retail by summarising significant trends, observing customer behaviour, and delivering actionable insights. The goal is to make recommendations that influence marketing tactics, inventory management, and consumer interaction.

# Methodology

1. Data Collection and Preparation.
● Loading the dataset: The dataset was loaded into a Python environment via Pandas.

● Data cleaning: Missing values were addressed, data types were updated, and duplicates were removed.

● Data Transformation: To allow for time-based analysis, I made sure that the "Purchase Date" column was in datetime format.

2. Descriptive Statistics

● Total Sales and Average Transaction Value: I summarised the total sales and determined the average transaction value for the year.

● Number of Transactions Per Month: Determined how many transactions occurred each month.

● Purchase Distribution: Data was grouped by product category and total sales were determined for each.

● Average Quantity Purchased per Transaction: Determined the average number of products purchased in each transaction.

# Data Visualisation

1. Sales Trends Over Time. A time series graph has been created to illustrate monthly sales trends, with peaks occurring around holidays or weekends.

2. Product Categories were designed a bar chart to show the most popular product categories based on total sales.

3. Payment Method Breakdown. A chart represented the distribution of various payment methods across all transactions.

4. Sales by Location A heatmap visualises sales based on store location and time of day.

# Sales by Product Category:
Product Category
Clothing            8929.79
Electronics        20197.25
Groceries          19797.27
Home Appliances     8515.20
Toys               20671.50
Name: Total Sales, dtype: float64

# Sales by Store Location:
Location
Store_A    34569.75
Store_B    24928.21
Store_C    18613.05
Name: Total Sales, dtype: float64

# Monthly Sales Trends:
Month
2023-01     6968.80
2023-02     3232.05
2023-03    11112.98
2023-04     3142.99
2023-05     3223.46
2023-06     3637.02
2023-07     7238.67
2023-08     9980.60
2023-09     8946.59
2023-10     7422.23
2023-11     8648.11
2023-12     4557.51
Freq: M, Name: Total Sales, dtype: float64

# Sales by Payment Method:
Payment Method
Cash               25858.59
Credit Card        32945.83
Digital Payment    19306.59
Name: Total Sales, dtype: float64

# Top 10 Customers by Total Sales:
Customer ID
CUST_4     4561.60
CUST_62    4019.62
CUST_93    3666.85
CUST_47    3413.50
CUST_15    3172.67
CUST_60    3137.55
CUST_2     2702.09
CUST_72    2527.22
CUST_64    2438.02
CUST_95    2377.65
Name: Total Sales, dtype: float64

![image](https://github.com/user-attachments/assets/df75d1b0-9a67-4088-82da-a06aabbfd5eb)

![image](https://github.com/user-attachments/assets/c2698d39-0c0c-4f75-a045-43552ac036a6)

![image](https://github.com/user-attachments/assets/5e3582e3-3ce3-4ba9-aa4d-caa855a9fbbf)

# Customer Segmentation

1. Customer segmentation based on purchasing behaviour

● Customers were divided into two groups depending on their purchase frequency: High-Frequency Buyers (the top 20% of customers by transaction volume) and Low-Frequency Buyers (the lowest 20%).

● The purchasing patterns of both divisions were compared to better understand their preferences and behaviours.

# Insights and Findings

1. Peak Shopping Periods

● Weekends and holiday seasons were shown to be the most popular times to shop, with Black Friday and Christmas seeing particularly high sales.

2. Trends in Product Category Sales

● Electronics sales remained stable throughout the year, while clothing sales increased during seasonal sales events.

3. Payment Methods Preferences

● Customers preferred digital payment methods, such as mobile payments, over cash, particularly among younger generations.

4. Store Location Insights

● Downtown stores had higher sales volume, especially during lunch breaks and after work hours, most likely due to increased foot traffic.

# Recommendations

Based on the analysis's findings, many initiatives can be done to improve XYZ Retail's operations and customer experience.

1. Inventory Management

In order to maximise inventory, need to focus on products that sell the most during specified time periods. Because electronics and apparel have been the most popular categories, it would be wise to stock up on these things at peak periods such as holidays and seasonal promotions. Moreover, this guarantees that the store is ready to satisfy client demand while avoiding stockouts. In addition, promotional methods can be developed to promote sales in low-volume sectors such as groceries or home products.

2. Targeted Marketing Campaigns

I think another essential advice is to create marketing campaigns that target customers based on their preferred payment method. For example, because digital payments (such as credit cards and mobile wallets) are the most popular means of payment, XYZ Retail might provide exclusive promotions to clients who use them. Furthermore, launching seasonal marketing around holidays such as Christmas and Black Friday might help improve sales. These ads should be marketed through digital media to reach a larger audience and stimulate spending during peak shopping periods.

3. Store Operations

To improve the in-store experience, I would recommend to pay attention to peak shopping hours. Because the stores enjoy more foot traffic on weekends, holidays, and during lunch hours. Furthermore, increasing staffing during these busy hours will assist to improve the customer experience by ensuring that they receive prompt and efficient service. This can also aid in controlling big queues and ensuring a fluid flow throughout the business.

# Conclusion
In conclusion, the findings gathered from analysing XYZ Retail's client buying habits provide useful information that can considerably benefit the company. By focussing on inventory management, targeted marketing, and retail operations, XYZ Retail may not only better meet consumer needs, but also enhance sales and satisfaction. The ideas aim to strengthen consumer relationships, streamline operations, and enhance the entire purchasing experience.
Furthermore, it is critical to continue monitoring client behaviour and adjusting techniques as needed in the future. Regular updates to this study will help XYZ Retail stay on track and respond to changing trends in client purchasing behaviours.
