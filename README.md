# pharma_sales_analysis
 Power BI project to analyze pharmacuetical sales data

### LinkedIn Post Link
I have made a post upon completing this project and posted it on LinkedIn. Here is it's link.
https://www.linkedin.com/feed/update/urn:li:activity:7153628776264810496?utm_source=share&utm_medium=member_desktop

### Dataset Information

The data is stored in Pharma_data_analysis.xlsx. This dataset contains 254,083 rows and 18 columns namely 1)Distributor	2)Customer Name	3)City	4)Country	5)Latitude	6)Longitude	7)Channel	8)Sub-channel	9)Product Name	10)Product Class	11)Quantity	12)Price	13)Sales	14)Month	15)Year	16)Name of Sales Rep	17)Manager	18)Sales Team

### Questions

1. Schema Design: Given the provided dataset, create a Power BI data model with appropriate tables and relationships, considering the Distributor, Customer Name, City, and other relevant columns. 
2. Relationships: Establish the necessary relationships between the tables in your data model. For instance, connect the "Sales" table to the "Customers" table. 
3. Role-Playing Dimensions: In your data model, demonstrate how you'd handle role-playing dimensions for "Sales Rep" and "Manager." 
4. Schemas: Build a star schema based on the data and explain how your schema design helps optimize report performance. 
5. Row-Level Security: Set up row-level security in your data model, restricting access for a specific sales team. Show which measures are affected. 
6. Calculated Columns vs. Measures: Calculate the total sales for each product both as a calculated column and a measure. Compare the results and explain the differences. 
7. Time Intelligence: Using DAX, create a measure that calculates the year-to-date (YTD) sales for each month. 
8. Filter Context vs. Row Context: Write a DAX calculation that shows the total quantity sold by each sales rep. Explain how filter and row contexts apply. 
9. Ranking: Create a DAX measure that ranks products by sales. Display the top 5 products by rank in a visual. 
10. Parent-Child Hierarchies: If there's a hierarchy in your data, such as categories and subcategories, create a DAX measure to summarize sales at the subcategory level. 
11. Drill-Through: Build a report where users can drill through from a summary to detailed data. For example, starting from a map, drill through to a table of individual sales for a specific city. 
12. Custom Visuals: Use a custom visual in your report to visualize sales data in a unique way. Explain why you chose this custom visual. 
13. Bookmarks and Buttons: Create a report with bookmarks and buttons that allow users to navigate between different pages or states within the report. 
14. Conditional Formatting: Apply conditional formatting to a measure so that it changes color when sales exceed a certain target value. 
15. Calculated Columns: Add a calculated column to your data model that calculates the total cost of each product (Quantity x Price). 
16. New Column from Example: Use the "New Column from Example" feature to add a column that categorizes cities into regions based on a predefined mapping. 
17. Time-Based Calculations: Create a measure that calculates the year-over-year (YoY) growth in sales for each month. 
18. Cumulative Total: Develop a measure to show the cumulative total of sales over time and visualize it in a line chart.

### Instructions on how to run this project code on your system
Step 1 : Download this project repository as a zip file. 
Step 2 : Unzip the folder to your desired location 
Step 3 : If you don't have Microsoft Power BI Desktop Installed , go to https://www.microsoft.com/en-in/download/details.aspx?id=58494&msockid=39cd1c66ce6867ae13a2094ecfc066fd, download the suitable installer, install Microsoft Power BI Desktop and launch it. 
Step 5 : Navigate to this project folder. 
Step 6 : When inside navigate to Pharma_Sales_Analysis.
Step 7 : Open the Pharma Analysis Report.pbix using Microsoft Power BI Desktop.
Step 8 : Go through the Questions mentioned above and compare the visuals in the Power BI File accordingly.

### Purpose of Solving this problem

Analyzing pharmaceutical (pharma) sales data using Power BI provides critical insights that can drive sales strategies, enhance customer engagement, and optimize business operations in the competitive pharma industry. Power BI’s robust visualization and analytical tools make it easier to derive actionable intelligence from complex datasets. Here are the key purposes of analyzing pharma sales data using Power BI:

#### 1. Sales Performance Analysis
Sales Trends: Track sales over time (monthly, quarterly, annually) to identify growth patterns or declines.
Product-Level Insights: Evaluate which drugs or products contribute the most to revenue.
Territory Performance: Analyze sales by geography to identify high-performing and underperforming regions.

#### 2. Market Demand and Forecasting
Demand Analysis: Understand product demand patterns by analyzing sales volume across regions, demographics, or seasons.
Forecasting: Use historical data to forecast future sales and prepare for inventory or marketing needs.
New Product Launches: Assess the impact of newly introduced drugs on sales.

#### 3. Customer and Physician Insights
Customer Segmentation: Identify and segment key customer groups such as healthcare providers, pharmacies, and hospitals.
Physician Preferences: Understand prescription patterns by doctors to tailor marketing and sales strategies.
Loyalty Programs: Evaluate the success of programs designed to engage pharmacies or physicians.

#### 4. Sales Team Performance
Sales Representative Metrics: Monitor the performance of individual sales representatives or teams.
Incentive Effectiveness: Assess how incentive plans impact the performance of sales teams.
Coverage Analysis: Identify gaps in sales team coverage across regions or target customers.

#### 5. Revenue and Profitability Optimization
Profit Margins: Analyze product profitability to focus on high-margin drugs.
Cost Analysis: Identify sales-related costs and optimize expenditures such as promotional expenses.
Pricing Strategies: Monitor the impact of price changes on sales volume and revenue.

#### 6. Inventory and Supply Chain Management
Stock Monitoring: Ensure optimal inventory levels to prevent stockouts or overstocking.
Distribution Efficiency: Analyze the performance of distribution channels to identify bottlenecks.
Expiry Management: Monitor near-expiry products to prioritize their sales.

#### 7. Competitive Analysis
Market Share: Analyze the company’s market share in comparison to competitors.
Pricing Strategies: Compare product pricing with competitors to remain competitive.
Customer Retention: Identify factors leading to customer churn and develop strategies to retain clients.

#### 8. Regulatory Compliance and Reporting
Compliance Tracking: Monitor sales data to ensure compliance with pharma regulations.
Reporting to Authorities: Generate detailed sales reports required by regulatory bodies.

#### 9. Marketing Campaign Effectiveness
Campaign ROI: Evaluate the return on investment for marketing campaigns targeted at physicians, hospitals, or consumers.
Promotional Impact: Track the impact of discounts or promotional offers on sales.
Customer Engagement: Measure the effectiveness of educational initiatives or awareness programs.

### Why Use Power BI?
Power BI is ideal for analyzing HR data because of its:

Interactive Dashboards: Create dynamic dashboards for real-time monitoring of sales performance.
Data Integration: Combine data from CRM systems, ERP platforms, and third-party sources for comprehensive analysis.
Advanced Analytics: Leverage built-in AI features to uncover hidden patterns or anomalies.
User-Friendly Interface: Enable non-technical users, such as sales teams, to explore data independently.
Custom Reporting: Generate role-specific reports for stakeholders like sales managers, regional heads, or marketing teams.

#### Key Outcomes

Enhanced Sales Strategies: Identify growth opportunities and improve targeting efforts for customers and regions.
Operational Efficiency: Streamline inventory management and reduce wastage from expired products.
Improved Customer Engagement: Build stronger relationships with physicians, pharmacies, and hospitals.
Data-Driven Decision Making: Empower stakeholders with actionable insights for informed planning and execution.
Increased Revenue: Optimize pricing, promotions, and sales team performance to maximize revenue and profitability.

By using Power BI to analyze pharma sales data, organizations can transform their sales operations, improve decision-making, and stay ahead in a competitive industry.











