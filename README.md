# NovaMed-Solutions 
Sales Performance Analysis and Reporting


-[Project Overview](#project-overview)

-[Recommendations](#recommendations)


---
## 📊 Project Overview

NovaMed is a leading pharmaceutical distributor facing challenges in optimizing sales performance, managing inventory efficiently, and identifying key market opportunities. These inefficiencies have impacted overall operational effectiveness and decision-making.

To address these challenges, this project applies data analysis techniques to uncover actionable insights and support data-driven decisions.

## 🔍 Analysis Conducted

📈 Top & Bottom Performance Analysis

-Tracks key sales metrics

-Identifies top-performing and underperforming drugs

-Highlights high-value and low-performing customers

👥 Customer Analysis

-Analyzes customer demographics

-Examines revenue distribution by buyer type

-Evaluates purchasing behavior


---
## 🛠️ Tools Used

-Power BI Desktop – Data import, cleaning, transformation, modeling, analysis, and visualization

-Power Query – Data cleaning and transformation across multiple CSV files

-DAX (Data Analysis Expressions) – Creation of calculated columns and measures for KPIs and performance analysis

-CSV Files – Source data format for customer, drug lookup, and fact tables


---
## 🔄Data Workflow

**1. Data Extraction**

The dataset consisted of three CSV files:

-Customer Table – customer demographics and attributes

-Drug Lookup Table – drug details and classifications

-Fact Table – transactional sales data

All files were imported into Power BI for analysis.

**2. Data Preparation**

Data types were validated, column names standardized, and initial data quality checks were performed across all tables.

**3. Data Cleaning (Power Query)**

Power Query was used to remove duplicates, handle missing values, and correct inconsistencies across the customer, drug lookup, and fact tables.

**4. Data Transformation**

Relevant fields were transformed and new calculated columns were created to support analysis. Date fields were formatted, and categorical values were standardized.

**5. Data Modeling**

A relational data model was built by establishing relationships between the fact table and the customer and drug lookup dimension tables, forming a star schema.

**6. Data Analysis**

Exploratory and performance analyses were conducted using DAX measures to evaluate sales trends, customer behavior, and product performance.

**7. Data Visualization**

Interactive dashboards were developed using charts, slicers, and filters to enable dynamic exploration of insights.

**8. Insights & Reporting**

Key insights and actionable recommendations were derived to support strategic decision-making.


---
## 🎯Key Sales Indicator

Total Quantity Sold = 269k

Total Cost of Goods Sold = 12.85M

Total Revenue = 71.31M

Total Profit = 58.45M

Total Profit Margin = 81.97%

Average Revenue Per Customer = 356.54k

Number of Country = 6

Number of Customer = 200


---
## 💡Key Insights

•The Profit Margin indicates that the company is doing well in managing its expenses in relation to its revenue. 

•The slack period happened the most in the month of February with August coming next.Other slack period happened in the following month; April, June, October and December.

•The peak periods include; January, March, May, July, September, November. The month of March happens to be the highest peak with September  coming next.

•Doxycycline is the best performing drug based on Profit and Revenue. Lisinopril is the best performing based on sales volume. Montelukast is the least performing drug based on profit, Warfarin is the least performing drug based on revenue, Omeprazole is the least performing drug based on sales volume.

•Bob Williams with Customer ID (191) is the top performing customer with 0.91% sales Contribution. Bob Williams generated total sales volume of 2.44k, profit of 639.19K and revenue of 803.62k. 

•Based on Profit,Jane Williams(200) is the underperforming customer.

•Based on Revenue and Sales Contribution,John Jones(47) is the underperforming customer. 

•Based on age distribution,the Old Adult (60-79) generated the most revenue. 

•Based on gender distribution,the Male category generated the most revenue.

•Based on buyer type,the Seller Category generated the most revenue.

•United States is the country with the least revenue with 2.2M new customers, 1.19M frequent customers and 2.12M preferred customers.

•Canada emerges as the country generating the most revenue of 31.67M, with 11M new customers, 7.2M frequent buyers and 13.4M  preferred customer.

•Canada and Australia are the top 2 countries based on revenue share.


---
## 📝Recommendations

•Market strategies adopted in Canada should be analysed and see if it can be implemented in other countries with low sales. 

•More discounted promo during the slack periods, most especially in February, August and October. Also, promo in regions with low sales like USA and France.

•Market presence should be strengthened through strategic marketing campaigns and especially in areas with low sales as stated above.

•NovaMed should place greater emphasis on collaborative partnerships with hospitals and other health agencies.

•Market research should be conducted to understand the “User category” needs. Also, affordability should be improved for this category.

•Inventory levels of top performing drugs should be increased while that of the low performing drugs should be monitored closely and carefully to avoid excess stock , expiry and financial loss.

•Customer engagement; Loyalty perks to reward performance should be put in place for top performing customers. Market research should also be conducted for low performing customers to understand reasons for low purchase.


---
## ✅ Conclusion

This analysis highlights the importance of proper data modeling in Power BI, particularly the use of unique identifiers to ensure accurate relationships and reliable insights. Additionally, the findings show that high sales volume does not always equate to high profitability, for example, while Lisinopril recorded high sales volume, it did not generate the highest profit. This underscores the need to track both revenue and profit metrics when evaluating product performance and making strategic decisions.












