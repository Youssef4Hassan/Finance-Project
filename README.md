#Finance Dashboard


Extracted data from Excel and performed ETL using Power Query.

Built a Snowflake Schema and created measures using DAX.

Developed 3 interactive dashboards in Power BI:


1. Revenue Analysis:

Shows Revenue, Cost, and Gross Margin by month.

Highlights top-selling products and best months.

Tooltips provide month-over-month comparisons and product details.



Analyzes sales by supervisors and salespersons (revenue, profit, and cost).

Tracks supplier performance and supplied product details.



Compares revenue across different price categories (high vs. low)

2. Finance Analysis

Analyzes sales, profit, cost, expenses, net profit, and cash flow.

Provides detailed account breakdowns using P&L, horizontal analysis, and vertical analysis.


3. Forecasting & What-If Scenario Dashboard:

Simulates how changes in price, quantity, cost, and expenses affect key metrics like revenue, gross margin, operating income, and profitability.

Combines with market research to guide decisions that boost profit and cut costs while avoiding risky actions that harm sales


Step 1 : Load data into Power BI Desktop From dataset is a Excel file.

![Image](https://github.com/user-attachments/assets/482f9a98-5361-44da-848a-a53d7ab44933)

Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options

![Image](https://github.com/user-attachments/assets/29d86936-f234-47a9-9fd8-04fd9b09fad7)

Step 3 : Also Check Data Valid by use Captlize Each Word & Trim, detect Data type".

![Image](https://github.com/user-attachments/assets/ceb8df4d-996d-4759-bf42-9218a9ce6953)

Step 4 : Unpivot other col to make tabular

![Image](https://github.com/user-attachments/assets/7dda16a6-7acf-41bb-9d26-2ce24fe2bf12)

Step 5 : Remove top rows

![Image](https://github.com/user-attachments/assets/a5c668ad-4811-40a9-8bde-97b3c109ae88)



Step 6 : Split col to provide data model

![Image](https://github.com/user-attachments/assets/9b888de1-851e-4145-b0a3-3f4139d222da)


Step 7 : Create Data Model (Snowflake)

![Image](https://github.com/user-attachments/assets/fc6e99f9-8121-498a-a5c4-08d2bf303b5e)

Step 8 : measure By DAX 

![Image](https://github.com/user-attachments/assets/c4e551dc-fc36-417a-8345-9c57dc009e88)

Step 9 :Bulid Revenue Dashboard

Create Three Cards (Revenue,Gross Margin,Cost) 

metrics
Revenue By month
Gross Margin By month
Cost by month
Revenue & Gross Margin & Cost by supervisor & salesperson
Revenue By supplier
Revenue By price categories

![Image](https://github.com/user-attachments/assets/f8af489c-6b40-4db3-b9ad-f6d8a26b53ab)

Step 10 : Build Tooltips to Month to know more details 

![Image](https://github.com/user-attachments/assets/03b9693a-c42f-42d4-8d31-c2fce59dbd3b)

Step 11 : Build Tooltips to supplier to know more details

![Image](https://github.com/user-attachments/assets/2402d82f-6664-4540-8fff-8bcec5f7d8ef)

Step 12 : Create Visual filtersin bookmarks  (Slicers) were added for Three fields named "Quarter", "Team","Category". 

![Image](https://github.com/user-attachments/assets/568c61c1-131d-48b1-ad96-41c500a85df1)

Step 13 : Bulid Finance Dashboard

Create Five Cards (Revenue,Gross Margin,Cost,expenses,operating income)

![Image](https://github.com/user-attachments/assets/abfca76d-b682-4123-908b-3a7a41c55020)

Step 14 : Bulid What If Dashboard

Create Five Cards (Revenue,Gross Margin,Cost,expenses,operating income)

Revenue By product

![Image](https://github.com/user-attachments/assets/2f04c8e0-b1e4-49c8-aac3-cd40f90f3e6e)
