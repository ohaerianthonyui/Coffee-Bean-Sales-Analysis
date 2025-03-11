# Coffee-Bean-Sales-Analysis




### Data Analysis Project: Coffee Sales Analysis (2023-2024)

#### **Introduction:**
This dataset contains coffee sales data over 2 years in Saudi Arabia, covering purchases from 100 customers across 5 different coffee Bean types. It includes details on quantity, pricing, discounts, and total sales, making it ideal for analyzing purchase trends, price impact, and market behavior.
The purpose of this analysis is to evaluate the coffee sales performance from January 1, 2023, to December 31, 2024, with a focus on revenue, quantity sold, product performance, and geographical trends. The analysis aims to identify key factors influencing sales, customer behavior, product preferences, and market performance. Using Power BI, this report will provide actionable insights for decision-making in areas such as product inventory, marketing strategies, and regional targeting.

#### **Objectives:**
The primary objectives of this data analysis project are:
1. **Revenue and Quantity Trends:** Analyze total revenue and quantity sold over time (monthly, quarterly, and yearly) to identify performance trends.
2. **Product Analysis:** Evaluate which coffee products (Brazilian, Ethiopian, Colombian, Costa Rica, and Guatemala) contributed most to the sales and which ones received the highest discounts.
3. **Regional Analysis:** Identify which cities contributed the most to sales and highlight areas with the least sales.
4. **Discount Analysis:** Investigate how discounts impacted the overall sales for each product.
5. **Sales Forecasting:** Forecast the total revenue for 2025 based on historical sales data, providing insight into future business planning.

#### **Methodology:**

The analysis was conducted using the following steps:

1. **Data Collection:**
   - The dataset contains the following columns: Date, Customer_ID, Category (Coffee Beans), Product (Brazilian, Ethiopian, Colombian, Costa Rica, Guatemala), Unit Price, Quantity, Sales Amount, Used Discount (True/False), Discount Amount, and Final Sales.
   
2. **Data Preparation in Power BI:**
   - The dataset was loaded into Power BI for cleaning, transforming, and aggregating the data. 
   - Key measures were created to calculate:
     - **Total Revenue:** Sum of Sales Amount.
     - **Total Quantity Sold:** Sum of Quantity.
     - **MTD (Month-to-Date), QTD (Quarter-to-Date), and YTD (Year-to-Date):** Aggregated totals to assess current period performance.
     - **YOYTD% (Year-Over-Year Growth):** Percentage growth compared to the same period last year.
   
3. **Visualizations:**
   - **Line Charts:** To track revenue and quantity trends over time.
   - **Bar Charts:** To compare product sales, discounts, and regional performance.
   - **Scatter Plots:** To assess the relationship between quantity sold and final sales, and the impact of discounts on sales.
   - **Forecasting Models:** Power BI’s forecasting feature was used to predict revenue for 2025 based on historical trends.

4. **Analysis Tools:**
   - Power BI was used for real-time data manipulation, interactive dashboards, and visual storytelling, enabling quick insights and actionable recommendations.

#### **Findings:**

1. **Overall Sales Performance:**
   - **Total Revenue:** The total revenue over the two years was **$630,000**, with a **Total Quantity Sold** of **19,000 units**.
   - **MTD Sales:** **$26,000** in the current month.
   - **YTD Sales:** **$316,000**, accounting for nearly half of the total revenue.
   - **QTD Sales:** **$74,000** during the current quarter.
   - **YOYTD% Sales:** There was a **1.07%** increase in sales compared to the previous year.
   - **MTD Quantity Sold:** **797 units**, **YTD Quantity Sold:** **10,000 units**, **QTD Quantity Sold:** **2,000 units**.

2. **Product Performance:**
   - **Best-Selling Product:** The **Colombian coffee** led in total sales with **$144,776**, followed by **Costa Rica** at **$141,078**.
   - **Highest Discounted Product:** The **Colombian coffee** received the highest discount at **$18,100**, followed by **Costa Rica** at **$14,700**.
   
3. **Regional Performance:**
   - **Best-Selling City:** **Hail** led with **$77,000**, followed by **Jeddah** with **$72,000**.
   - **Least Performing City:** **Tabuk** recorded the lowest revenue at **$51,000**.
   - **Top Cities in 2023 and 2024:**
     - In 2023, **Jeddah** (41k) and **Riyadh** (37k) were the top-performing cities.
     - In 2024, **Hail** (46k) and **Medinah** (35k) led in sales.

4. **Sales by Quarter:**
   - **Best Quarter in 2023:** The **first quarter** had the highest sales at **$82,000**, with **Q4** trailing behind at **$74,000**.
   - **Best Quarter in 2024:** The **third quarter** saw the highest sales at **$85,600**, with the **fourth quarter** at **$74,400**.

5. **Forecasting for 2025:**
   - The forecasted total revenue for 2025 is **$319,849**, based on historical sales data and trends.

#### **Conclusion:**

The sales data reveals several key trends and performance insights:
1. **Product Performance:** Colombian coffee consistently led both in total sales and discounts, while Costa Rica and Ethiopian coffee also performed well.
2. **Geographical Performance:** Sales in **Hail** and **Jeddah** were notably higher compared to other regions, suggesting stronger demand or more effective marketing in those cities.
3. **Discount Impact:** High discounts on Colombian coffee did not seem to negatively affect its sales, indicating that discounts may boost sales but should be monitored for profitability.
4. **Year-over-Year Growth:** A modest YOYTD sales increase of **1.07%** suggests steady, but slow growth, possibly due to market saturation or seasonal fluctuations.

#### **Recommendations:**

1. **Focus on High-Selling Products:** Continue to promote **Colombian** and **Costa Rica** coffees, as they have shown strong sales performance. Consider introducing new flavors or packaging to further boost sales.
2. **Regional Marketing Strategy:** Given that **Hail** and **Jeddah** are top-performing cities, targeted marketing efforts, loyalty programs, and promotional campaigns should be prioritized in these areas. Expand outreach to **Tabuk**, where sales are currently lower.
3. **Optimize Discount Strategies:** While discounts are effective for driving sales, especially on Colombian coffee, it is important to ensure that the discount strategy doesn't erode margins excessively. Adjust discount levels based on the performance of each product.
4. **Increase Forecast Accuracy:** Regularly update the forecasting model based on seasonal data and market shifts to improve revenue predictions. Consider adding external factors, such as market trends and consumer behavior changes, to refine forecasts further.
5. **Explore Underperforming Products and Regions:** Reevaluate marketing and sales efforts for products like **Brazilian** and regions like **Abha**, which have been underperforming.

With these insights and recommendations, the company should be able to tailor its strategies to maximize revenue, optimize product offerings, and improve market penetration.
