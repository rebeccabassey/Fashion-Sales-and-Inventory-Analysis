# Fashion-Sales-and-Inventory-Analysis
A fashion retail sales data analysis that supports better stock management, pricing strategy, and product planning.
Sales and Inventory Data Analysis (30DaysDataChallengewithAnnie)
This project documents my work for Day 19–21 of the #30DaysOfDataWithAnnie challenge, where I cleaned and explored a real-world fashion retail dataset to generate actionable insights for business decision-making.

🌟 Project Overview
Goal: Prepare and analyze a fashion inventory dataset to support better stock management, pricing strategy, and product planning.

Dataset: Sales_and_Inventory-Fashion_Inventory_Clean.xlsx (15,000 rows, 13 columns)

✅ Business Problem
How can the retail brand manage stock levels, optimize pricing, and understand demand by product type to reduce stock-outs and overstock, improving sales and customer satisfaction?

🧹 Data Cleaning Steps
I cleaned the raw data in Google Sheets using these steps:

Handled Missing Values: Filled blanks with N/A for transparency

Standardized Formats: Reformatted dates and extracted "Month" into a new column

Fixed Inconsistent Values: Standardized product sizes (e.g., “XL”, “5-6yo”)

Removed Duplicates: Ensured unique records

Verified Data Types: Set proper formats for dates, prices

Created New Columns:

Month (extracted from Date)

Stock Status Numeric (1 for In Stock, 0 for Out of Stock and blanks for N/A

In stock and Out of Stock Price

🔎 Exploratory Data Analysis (EDA)
I explored the cleaned data with pivot tables and statistical tests:

📌 Key Pivot Table Questions & Insights

1️⃣ Which Categories Sell Most?

Top: Straight Kurta (3,724), A-Line Kurta (1,590)

Insight: Focus on restocking popular kurta types

2️⃣ Average Selling Price by Product Type

Highest priced: T-shirt (65,400)

Lowest priced: Kurta with Printed Inner (3,890)

Insight: Pricing varies significantly by category

3️⃣ Brand Stock Count

Highest stock: Anouk (1,725)

Lowest stock: Multiple brands with just 1 item

Insight: Many low-stock brands → possible delisting or marketing opportunities

4️⃣ Monthly Inventory Trend

Peak Months: August, July, June

Low Months: February, September, May

Insight: Plan seasonal stock levels better

📈 Inferential Statistics

1️⃣ Correlation
Tested whether higher-priced items tend to have more or less stock

Result: Correlation coefficient = 0.002

Interpretation: No meaningful relationship; price doesn’t predict stock levels

2️⃣ T-Test
Compared prices of In-Stock vs Out-of-Stock items

Result: p-value = 0.794

Interpretation: No statistically significant price difference between stock statuses

📌 Key Takeaways
Popular categories should drive stock decisions

Wide pricing range suggests opportunities for segmentation

Seasonality needs better planning

Current pricing doesn’t explain stock availability → consider demand signals

🔗 Live Analysis / Documentation
📑 Google Sheet Link https://docs.google.com/spreadsheets/d/1CPYLi1NwFoDQG18HrTrBVbhOKGpWFCs86_PG5501Y1I/edit?usp=sharing

🤝 Acknowledgements
Special thanks to Deborah, my partner on this challenge, for collaborating on cleaning and analysis.

💻 How to Use This Project
Clone the repo or download the spreadsheet

Review the cleaning steps and EDA insights

Adapt the methods for your own retail data

