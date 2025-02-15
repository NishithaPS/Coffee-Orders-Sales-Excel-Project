**Comprehensive Analysis of Coffee Orders Data Using Excel**

**1. Introduction**

This project focuses on analyzing coffee order data to gain insights into customer behavior, sales performance, and product popularity. The dataset consists of three key components:

  •	Orders Data: Contains transaction details such as order date, customer ID, product ID, quantity, and sales.
  
  •	Customers Data: Provides information on customer demographics, including country, loyalty status, and contact details.
  
  •	Products Data: Lists product details like coffee type, roast type, size, and pricing.

To make the analysis interactive, a dashboard was created with the following key elements:

  •	Pivot tables for:
  
      o	Top 5 customers by total sales
      o	Total sales calculation
      o	Sum of sales per country
    
  •	Dashboard visualizations including:
  
      o	Total sales over time (line chart)
      o	Sales by country (bar chart)
      o	Top 5 customers (bar chart)
    
  •	Slicers for dynamic filtering by:
  
      o	Order Date
      o	Roast Type Name
      o	Size
      o	Loyalty Card
      
This structured approach allows for effective data exploration and strategic decision-making.
________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________
**2. Data Preparation and Transformation**

  Handling Missing Values
  
  •	Any missing values in sales calculations were handled by ensuring the derived column was correctly computed as: 
                          Sales=Quantity×Unit Price
                          
  •	Missing customer details were cross-referenced using Customer ID from the customers dataset.
  
  Data Merging
  
  •	The datasets were combined using Customer ID (to fetch customer details) and Product ID (to fetch product pricing and attributes).
  •	This allowed for a holistic view of each order, including who placed it, what was bought, and how much revenue it generated.
  
  Derived Columns
  
  •	Sales: To measure revenue contribution per order.
  •	Customer Segmentation: To classify customers based on purchase frequency and total spend.
  •	Product Segmentation: To group coffee products based on roast type, size, and country preference.
________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________
**3. Key Insights from Pivot Table Analysis**

    1. Top 5 Customers Analysis
       
      A pivot table was created to rank customers by total sales contribution.
      
      Findings:
      
      •	The top 5 customers accounted for a significant percentage of total revenue.
      •	Customers with loyalty cards showed higher average purchase values, indicating that the loyalty program positively influenced spending habits.
      •	Some customers had higher order frequency but lower average transaction values, while others made fewer but high-value purchases.
      
      Business Impact:
      
      •	Implement exclusive loyalty rewards for top customers to increase retention.
      •	Offer personalized promotions to high-frequency but low-value customers to increase basket size.
________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________
    2. Total Sales Over Time (Line Chart)
       
      This chart was used to identify seasonal trends and revenue fluctuations.
    
      Findings:
      
      •	Sales showed clear seasonal patterns, with noticeable spikes during certain months.
      •	Promotions and discounts likely boosted sales in specific periods.
      •	Sales dipped in certain months, indicating potential for marketing efforts to drive consistent revenue.
      
      Business Impact:
      
      •	Schedule marketing campaigns and discounts during low-sales periods.
      •	Plan inventory and staffing based on seasonal demand.
      •	Use historical data to forecast future sales trends.
________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________
    3. Sales by Country (Bar Chart)
       
      A bar chart provided a geographical breakdown of sales.
      
      Findings:
      
      •	Some countries contributed significantly more to revenue than others.
      •	Emerging markets had lower total sales, but growth potential was observed.
      •	Certain roast types and sizes were more popular in specific regions.
      
      Business Impact:
      
      •	Focus on high-performing regions for further market penetration.
      •	Adjust product offerings based on regional preferences.
      •	Introduce localized pricing and promotions in underperforming regions.
________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________
    4. Product Performance Analysis
       
      By analyzing sales across different coffee types, roast types, and sizes, key insights were gained.
      
      Findings:
      
      •	Dark Roast was the most popular roast type, followed by Medium Roast.
      •	Larger sizes (500g, 1kg) generated higher sales revenue compared to smaller packs.
      •	Some coffee blends had high sales volume but lower profit margins, while others were premium but had fewer sales.
      
      Business Impact:
      
      •	Optimize inventory to stock more of the best-selling roast types and sizes.
      •	Introduce bundled discounts for slow-moving products.
      •	Increase marketing efforts for premium products to boost high-margin sales.
________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________
**4. Interactive Dashboard Features**

To enhance usability, slicers were implemented for Order Date, Roast Type, Size, and Loyalty Card Status.

  How These Slicers Help:
  
    •	Order Date Slicer: Allows users to view sales for specific time periods.
    •	Roast Type Slicer: Helps analyze which roast types are the most preferred.
    •	Size Slicer: Reveals customer preferences for product sizes.
    •	Loyalty Card Slicer: Compares spending behavior between loyalty members and non-members.
    
  Business Impact:
  
    •	Enables quick filtering to understand different aspects of sales data.
    •	Helps in strategic pricing decisions based on customer preferences.
    •	Supports targeted promotions by identifying what works best for different customer segments.
________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________
**5. Key Business Recommendations**

  1. Strengthening Customer Engagement
     
    •	Implement a tiered loyalty program to reward high-spending customers.
    •	Offer special discounts or early access to premium products for repeat buyers.
    •	Use customer purchase history for personalized marketing.
    
  2. Sales and Marketing Strategy
     
    •	Increase marketing efforts during off-peak months to boost revenue.
    •	Launch region-specific promotions to cater to country-based demand.
    •	Advertise best-selling coffee types and sizes more prominently.
    
  3. Optimizing Product Offerings
     
    •	Discontinue or redesign low-performing products.
    •	Introduce new variations of popular roast types.
    •	Offer subscription-based coffee delivery for high-frequency buyers.
    
  4. Expansion and Business Growth
     
    •	Consider expanding high-performing product lines.
    •	Explore new markets with potential growth opportunities.
    •	Partner with local coffee shops or distributors to increase reach.
________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________
**6. Conclusion**

This Excel-based analysis provided deep insights into sales trends, customer behavior, and product performance. With well-structured pivot tables, visualizations, and interactive slicers, the dashboard became an effective decision-making tool.

By acting on these insights, the business can:

  ✔ Enhance customer retention through personalized engagement.
  
  ✔ Maximize sales during off-peak periods with targeted campaigns.
  
  ✔ Optimize product offerings to align with market demand.
  
  ✔ Expand strategically based on regional and product performance trends.
  
  
This project demonstrates how Excel can be leveraged as a powerful data analysis tool to drive business decisions. 

