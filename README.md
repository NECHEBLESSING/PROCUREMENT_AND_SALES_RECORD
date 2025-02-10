# PROCUREMENT_AND_SALES_RECORD
# TABLE OF CONTENT
. [OVERVIEW](#overview)

. [DATA SOURCE](#data-source)

. [LANDING PAGE](#landing-page)

. [DATA TOOLS](#data-tools)

. [OBJECTIVE/KPIs](#objectivekpis)

. [DATA CLEANING](#data-cleaning)

. [DATA PROCESSING](#data-processing)

. [DATA ANALYSIS](#data-analysis)

. [INSIGHTS](#insights)

. [RECOMMENDATION](#recommendation)
## OVERVIEW
This dataset contains key business information related to procurement, sales, customer experience, and workforce productivity, it helps analyze financial performances. By leveraging this data, businesses can identify trends, optimize costs, improve sales strategies, and enhance customer experience.
## DATA SOURCE
This is an xlsx data gotten from a colleague 
## LANDING PAGE
This explains each column in the dataset;
-	**Date**: Represents the transaction or activity date.
-	**Region**: Indicates the geographical location where the transaction occurred.
-	**Product**: Specifies the name or category of the product involved in the transaction. It Essential for analyzing product-specific sales, revenue, and customer satisfaction.
-	**Suppliers**: Refers to the vendor or supplier providing the product.
- **Sold Unit**: Shows the number of units sold in a particular transaction.
- **Profit/Loss**: Indicates the financial outcome of the transaction:
- **Unit Cost Price**: The price paid to procure a single unit of the product.
- **Unit Selling Price**: The price at which a single unit of the product is sold.
-	**Procurement Cost**: Total cost of acquiring the product.
- **Customer Rating**: Represents customer satisfaction, usually on a scale (3-5).
- **Staff Name**: Indicates the employee handling the transaction or activity.
- **Employee Hours Worked**: The number of hours an employee spent working on the associated task or product.
- **Supplier Lead Time**: The time taken by the supplier to deliver the product after placing an order.
## DATA TOOLS
- Microsoft Excel: Data analysis
- Microsoft Powerbi: Dashboard, Data visualization 
## OBJECTIVE/KPIs
- Top performing profitable and Loss-making products and regions
- Analyze customer ratings to enhance product quality and service
- Track employee hours to identify workload distribution and efficiency.
- Detect seasonal sales trends, high-revenue regions, and procurement inefficiencies.
- Assess supplier efficiency, procurement costs, and lead times.
- Measures customer satisfaction per product/region
## DATA CLEANING
These processes were caried out using power query
- No duplicate was found in the dataset
- Time and Date formatting
- Customer Rating missing values where replace with the minimum rating which is (3)
## DATA PROCESSING
-	The data was checked for missing and inconsistent values
-	Total revenue column was added by (unit sold * unit selling price)
-	Profit/loss column was added by (unit cost price -unit selling price)
# DATA ANALYSIS
## A comprehensive performance rating analysis of;
•	**SALES BY PRODUCT:** **Scanner** generated the total sum revenue of $4,261,346 making the highest revenue and total unit sold is 376 making it highest sold product.  **Tablet** made the lowest total revenue generating the sum of $1,837,595 and has the least sold unit of 150

•	**SALES BY REGION:** **Northern Region** made the most sales generating the sum of $7,402,468 and having **Scanner** with the most sold unit in the **Northern, and East Region** generating the Lowest Revenue by Region $4,751,952

• **SALES BY SUPPLIERS:** **ElectroWorld** made the highest sales by suppliers generating $3,205,891 and making most sales from **Scanner**, and **TechSource Inc**. generating the Lowest sales by supplier with the sum of $1,902,241

•	**CUSTOMER RATING BY PRODUCT:**Smartwatch** has the most rated by customer rating with 15.66% and **Laptop** has the least Customer Rating of 6.8%

•	**CUSTOMER RATING BY REGION:** **Northern Region** has the most rated by customer rating with 28.06% and **East Region** with the least Customer rating of 22.68%

•	**CUSTOMER RATING BY SUPPLIERS:** **OfficeSupply Co**. has 11.58% the most Rated from the customer and Hardware Haven haing the least rating from customers with 6.68%

•	**BY SUPPLIERS LEAD TIME:**
    - **Scanner** lead time by supplier 16.68% having the most lead time and supplier **GadgetFlow** leading by 3.62%.
    - **Tablet** lead time by supplier 5.54% having the least lead time by supplier, **OfficeSupply Co.** leading the most in timing by 1.98%.

•	**BY PROCUREMENT COST:**
   - **Scanner** has the highest amount of procurement cost with $17
# DASHBOARD
![CSD](https://github.com/user-attachments/assets/14c78be6-04bf-4dca-9632-22612a1cc64d)
![customer experience](https://github.com/user-attachments/assets/163da22b-6f73-4fc2-b598-1e41ed91fceb)
![customers experience dashboard](https://github.com/user-attachments/assets/6ea4b982-3687-41d4-827f-084d9d26c05c)
![procurement dp](https://github.com/user-attachments/assets/cf301cc4-ea60-4589-bb0f-3e864b3de669)
![TOTAL REVENUE](https://github.com/user-attachments/assets/ba5be7c3-5f93-47bf-a22e-15bd3710094d)





# INSIGHTS
**1.	Financial Performance Insights**
-	Northern Region generates the highest revenue, while East Region has the lowest, indicating a need for targeted sales strategies.
-	Some transactions are losing money because the cost of buying the products is too high or the selling price is too low, reducing overall profits.
-	Certain high-selling products still have low profit margins, meaning pricing strategies need adjustment.
2.	**Customer Satisfaction Insights**
-	Products with higher customer ratings (above 4.5) have higher repeat purchases, indicating strong brand loyalty.
-	Northern Region consistently receives the highest customer ratings, suggesting better service or product availability.
-	Some highly rated products like smartwatch have low sales, showing an opportunity for better marketing or pricing adjustments.
3.	**Procurement Efficiency Insights**
-	Supplier hardwave haven offers the lowest cost prices, making them the most cost-effective choice.
-	Supplier Lead Times vary significantly, affecting product availability and possibly customer satisfaction.
-	Smart watch has high procurement costs but low sales need reassessment to reduce unnecessary expenses.
4.	**Workforce Productivity Insights**
-	Certain products require significantly more employee hours, impacting efficiency.
-	Southern Region has the highest employee workload, aligning with its high revenue but posing risks of burnout.
-	No clear correlation between more employee hours and higher customer ratings, suggesting inefficiencies in workforce allocation.
5.	**Trends and Patterns**
-	Seasonal trends indicate that revenue peaks in specific months sales go up and down at different times, so businesses should plan their inventory wisely to avoid running out of stock during busy periods or having too much during slow times.
-	When suppliers deliver products faster, customers are happier. Hence the importance choosing reliable suppliers to keep customers satisfied.
-	Some high-selling items might have low profit margins, while fewer sales of certain products could bring in more profit,
-	Profitability and sales volume don’t always align, meaning some high-selling products may not be the most profitable.
## RECOMMENDATION 
-	Prioritize suppliers with lower costs and shorter lead times to improve profitability and productivity.
-	Plan inventory and marketing campaigns around high revenue months to capitalize on seasonal demand.
- Redistribute tasks for products requiring excessive employee hours to enhance productivity and reduce burnout.
- Implement tailored strategies in low-performing regions to improve revenue and customer satisfaction.
- Promote high-rated but low-selling products to maximize their potential and boost sale





