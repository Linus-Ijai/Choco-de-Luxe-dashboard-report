# Choco-de-Luxe-dashboard-report
This report delivers a detailed examination of Choco de Luxe sales and delivery performance across Europe uncovering trend in regional sales channel efficiency, staff contributions, and product profitability using Ms. Excel

# Table of content

Introduction
Data preparation
Tools used
Understanding the dataset
Visualisation
Key findings
Conclusion and Recommendations

# Introduction
This report provides a technical analysis of Choco de Luxe’s sales and product performance across multiple dimensions—sales channels, product categories, geographies, personnel, and delivery status. The dashboards provided serve as the basis for descriptive analytics, with further interpretive insights included to support decision-making. The purpose of this report is to identify sales drivers, highlight inefficiencies, and recommend actionable strategies that enhance both operational and strategic outcomes.

# Data preparationt
This project analyzes chocolate sales performance across multiple dimensions — location, sales channel, salesperson, and product characteristics — to generate business insights such as channel effectiveness, location performance, salesperson productivity, and product profitability.
All datasets were merged into a single integrated fact table in Excel using unique identifiers as key columns.
All tables were merged using Excel’s Power Query merge functions based on their unique identifiers:

|Relationship|	Key Used|	Description|
|------------|----------|------------|
|Sales Fact ↔ LocationDim|	LocationID|	Adds country, city, and region details for each transaction|
|Sales Fact ↔ SalesPersonDim|	SalesPersonID|	Adds salesperson details for performance tracking|
|Sales Fact ↔ ProductD|	ProductID|	Adds product attributes and cost/price details|

# Tools Used
  1. Excel -For initaial data prtocessing, formula and structuring
  2. Power query - for merging and transfoirming data effenciency
  3. Excel - for visualsation, trend snalysids and generate insights
    
# Understanding the dataset
  This dataset represents chocolate product sales across different locations, sales channels, and salespersons.
It helps analyze performance, profitability, and demand patterns.
Main Tables and Roles:
  •	Sales Fact Table: Records each transaction — date, salesperson, location, product, boxes shipped, sales channel, and delivery status.
  •	Location Table: Adds country, city, and region details.
  •	SalesPerson Table: Contains salesperson names, emails, and hire dates.
  •	Product Table: Provides product names, categories, cocoa content, cost, price, and organic labels.

Key steps:
  •	Removed duplicates and filled missing values.
  •	Standardized text fields (e.g., delivery status, sales channels).
  •	Converted dates to YYYY-MM-DD format.
  •	Created calculated columns such as:
      o	Total Sales = Boxes Shipped × Price per box
      o	Profit = Total Sales – Total Cost
      o	Profit Margin (%) = (Profit / Total Sales) × 100
      o	Delivery Success Flag = IF(Delivery Status="Completed",1,0)

The final dataset, Chocolate_Sales, combines sales, location, product, and salesperson information for analysis.

Insights Derived:
  •	Location and channel performance
  •	Salesperson productivity vs. €100,000 target
  •	Product and category profitability
  •	Organic vs. non-organic product demand

# Visualisation
Screenshoot  of dashboard
https://github.com/Linus-Ijai/Choco-de-Luxe-dashboard-report/blob/main/Screenshot%202025-10-01%20211748.png

# Key Findings
  1. Overall Performance:
     a. Total sales: The company achieved strong sales figures 
     b. Average sales Value: An average sales per transaction is maintained, indicating good customer purchasing power.
  2. Choco de Luxe has a strong market presence but with concentrated dependencies.
  3. Over-reliance on a particular channel such as website introduces risk, while market concentration in Western Europe highlights growth opportunities in underdeveloped regions.
  4. The product performance is dominated by a few categories, suggesting the need for repositioning weaker performers.
  5. Personnel contributions are uneven, requiring interventions in training and incentive design.
  6. Seasonal fluctuations further underscore the need for proactive promotional planning.
  7. Monthly and Yearly Trends:
     The lines chart shows a seasonal trend in sales with peaks around certain months possibly festive period like December, this highlights the need for seasonal inventory planning and target campaigns ahead of high demand periods.

# Conclusion
  Choco deluxe maintains a strong sales performance driven by a handful high value customers and strong products. However, opportunities exist to diversify customer concentration, expand underperforming regions and optimize product mix. with strategic customer engagement target marketing and seasonal planning Choco deluxe can strengthen it market position and unlock further growth.

#  Recommendations
1.	Strengthen social media and warehouse sales to reduce dependency on website.
2.	Expand into underperforming countries with localized campaigns.
3.	Scale Dark and Milk Chocolate categories while repositioning or repackaging weaker products.
4.	Introduce performance incentives and coaching to balance personnel contributions.
5.	Plan seasonal campaigns during historically low-sales months (Feb, Aug).
7.	Boost social media sales by investing in ads and promotions.
8.	Optimize your website by making it more user friendly and attractive to encourage more usage.
9.	Position warehouses strategically across countries with high patronage.

  By Ijai Linus Jilmari
