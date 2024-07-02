# DatalineBike-SalesReport-PowerBI
This project leverages MS Power BI to create interactive data visualizations of sales data for the Dataline Bike Company. It includes key metrics such as revenue, sales growth, and customer demographics, providing valuable insights to enhance decision-making.

## Project Objective:

- Develop insightful Power BI reports to facilitate data-driven decision-making and meet the distinct analytical requirements of the CEO and the Marketing & Products team.


#### CEO Dashboard:

1. **Profit/Loss by Country**: Interactive map visualizing product profit/loss across countries with tooltip displaying profit development over time.
2. **Revenue Trends**: Line chart showcasing overall revenue development over time.
3. **Profit Breakdown**: Matrix visual with conditional formatting, displaying profit for all categories/subcategories for easy readability.

#### Marketing & Products Team Dashboard:


1. **Sales and Profit Analysis**
   - Total sales amount year-to-date.
   - Year-over-year profit difference.
   - Drill-down details page with order date, quantity, revenue, profit, product, and country.

2. **Customer Analysis**
   - Average profit per customer and its change over time.
   - Top 10 customers by revenue.

3. **Revenue and Profit Margins**
   - Revenue development over time by category.
   - Profit margin trends and identification of profitable categories, subcategories, and products.


## Technical Implementation:

- **Data Integration and Cleaning**: Integrated data from Dataline Bike Company's internal systems, including CSV files for sales and an Excel file with retail data. Conducted thorough data cleaning in Power Query Editor to ensure accuracy and consistency, including the creation of a robust date dimension for time-based analysis.

- **Advanced Analytics with DAX**: Implemented complex calculations and custom measures using DAX (Data Analysis Expressions) in Power BI. This included calculating revenue, profit margins, year-to-date figures, and profit comparisons, ensuring comprehensive financial insights.

- **Interactive Visualization and User Engagement**: Designed interactive visuals such as Clustered Column Charts, Pie Charts, and Line Charts to present sales and financial data effectively. Implemented drillthrough and drilldown features for detailed exploration and utilized report page tooltips to enhance data visibility and user experience.

- **Dynamic Filtering and Customized Views**: Incorporated slicers ,filters and tooltips to allow dynamic data interaction and customized views based on specific criteria. This enabled users to explore data subsets and gain deeper insights into sales performance and financial metrics.

## Insights from the report:

### Profit/Loss Analysis by Country:
- The highest Revenue of $9.2M and Profit of $3.8M is recorded by United States while the lowest of $1.9M and Profit of only $0.8M is recorded by Canada.

### Revenue Trends:
- The highest Revenue, Profit, and Cost is recorded in the year 2019 while lowest was recorded in 2017.


### Profit/Loss Analysis by Category:


- **Top Performing Category**: The Bikes category led in revenue and profit, totaling $28.3 million and $11.5 million respectively. Strong global demand and premium pricing contributed to higher revenue per unit sold.

- **Growth Opportunities**: Accessories and Clothing categories show significant growth potential. Accessories, with a higher profit margin than Clothing, present opportunities for strategic marketing and product development to enhance overall revenue and profitability.

- **Profit Margin Analysis**: Accessories achieved a notable profit margin of 63%, contributing 43.66% to total profits. This is attributed to lower production costs, higher markup rates, and less competitive pricing pressure. Additionally, their association as complementary products to bikes allows for premium pricing strategies.

- **Profitable Sub-categories**: Among accessories, Vests, Shorts, and hydration packs stand out as profitable sub-categories, contributing positively to overall profitability.


### Year-over-Year Profit Comparison:

- The highest YoY Profit Percentage change was recorded for the year 2019 indicates growth and a significant improvement in the business performance compared to the previous year. 


### Customer Analysis:


- **Profit per Customer Trend**: From 2017 to 2020, Dataline Bike Company has experienced a consistent upward trend in average profit per customer.

- **Average Profit per Customer**: As of the data, the highest average profit per customer stands at $233, which is a steady increase over recent years.

- **Drivers of Growth**: This growth reflects successful strategies in customer retention, effective upselling and cross-selling initiatives, and continuous improvement in product offerings and customer satisfaction.



### Interactive Features:

Certainly! Here's a refined version:

- **Interactive Data Exploration**: Slicers and filters empower users with dynamic data interaction, enabling customized views and in-depth analysis by Country, Products, and Category.
  
- **Enhanced Insight Accessibility**: Tooltips provide detailed insights upon hovering over charts, enhancing the user experience with instant access to additional contextual information.


## Conclusion:

This Power BI project serves as a robust analysis platform for Dataline Bike Company, equipping the CEO and Marketing & Products team with actionable insights that enhance reporting efficiency and support strategic decision-making. By leveraging Power BI's capabilities, the company not only improves data-driven decision-making but also aligns with its strategic objectives, ensuring continued growth and competitiveness in the market.
