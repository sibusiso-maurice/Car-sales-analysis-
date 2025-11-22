# Bright Motors Car Sales Analysis (BRIGHTLEARN) 
Purpose: Business Insights for a New Head of Sales using Historical Car Sales Data from 
Bright Motors 
1. INTRODUCTION & INSTRUCTIONS 
1.1 INTRODUCTION 
You have been provided with a dataset titled “Bright Car Sales”, which captures daily 
transactional and pricing information for vehicles sold by Bright Motors. 
Bright Motors has recently appointed a new Head of Sales, whose mission is to expand 
the dealership network, improve sales performance, and optimize inventory. Your role, as 
a Junior Data Analyst, is to extract actionable insights from the historical car sales data 
and prepare a presentation that will help guide future sales and marketing strategies. 
2. OBJECTIVE 
Use your data analytics, SQL, and data visualization skills to help Bright Motors 
understand:  
• Which car makes and models generate the most revenue  
• The relationship between price, mileage, and year of manufacture  
• Which regions or locations have the highest sales volumes  
• Emerging trends in customer purchasing preferences  
• Recommendations to increase dealership profitability and efficiency 
3. TOOLS ALLOWED 
You may use any of the following tools (or equivalents): 
Coding / SQL Platforms: 
• Snowflake 
• Microsoft SQL Server 
• Databricks 
• Google BigQuery 
• MySQL Workbench 
Data Visualization: 
• Microsoft Excel 
• Power BI 
• Google Sheets 
• Google Looker Studio 
Presentation / Reporting: 
• Microsoft PowerPoint 
• Canva 
Project Planning: 
• Miro  
• Figma 
4. TASKS (Detailed) 
Task 1 — Planning & Architecture (Miro or equivalent) 
Create a Miro board (or any whiteboard tool) that outlines: 
1. Data Flow / Architecture Diagram showing: 
o Source: car sales dataset (CSV/Excel file) 
o ETL Pipeline: data cleaning (e.g., removing duplicates, handling missing 
values, currency formatting) 
o Storage: Snowflake or chosen SQL database 
o Analysis Layer: SQL and visualization tools (Excel / Power BI) 
o Presentation Layer: PowerPoint / Canva 
2. Key Insights to Deliver: 
o Revenue by car make and model 
o Sales distribution by year and fuel type 
o Regional performance (city or province) 
o Average selling price trends over time 
3. Key Calculations: 
o Total_Revenue = Selling_Price * Units_Sold 
o Profit_Margin = (Selling_Price - Cost_Price) / Selling_Price * 
100 
o Grouping by Make, Model, Year, Region, and Fuel_Type 
Task 2 — Data Processing in Snowflake (or chosen SQL platform) 
Steps: 
1. Convert the provided Excel file into a CSV file.  
2. Load the CSV file into Snowflake (or equivalent).  
3. Perform data cleaning and transformations:  
• Convert text-based prices (e.g., ‘15,000’) to numeric format.  
• Create a new column total_revenue = selling_price * units_sold.  
• Calculate profit_margin and categorize cars by performance tiers (e.g., High 
Margin, Medium Margin, Low Margin). 
• Group transactions by time periods (month, quarter, or year). 
Task 3 — Data Analysis & Visualization (Excel / Power BI / Google Looker 
Studio) 
• After transforming your data in Snowflake, export the processed dataset to Excel or 
connect Power BI directly to your database. 
• Use slicers for region, fuel type, and year to allow interactivity. 
Task 4 — Presentation to the Head of Sales 
• Create a professional presentation that summarizes findings and 
recommendations. 
5. SUBMISSION GUIDELINES 
Required files: 
• Miro Plan / Architecture Diagram (image or link)  
• Processed Dataset Spreadsheet (car_sales_processed.xlsx)  
• Presentation File (BrightMotors_Presentation.pdf)  
• SQL Script (car_sales_queries.sql) 
6. TIPS & NOTES 
• Ensure all prices are converted to numeric formats (remove commas or currency 
symbols). 
• Handle missing or inconsistent values carefully. 
• Use clear and consistent column names in Snowflake. 
• Include short insight notes in your dashboards. 
• Your presentation should be visually appealing and concise. 
