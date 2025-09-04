Sales Performance Dashboard
Project Overview
This project demonstrates an end-to-end business intelligence workflow using SQL Server for data extraction and Excel for dashboard creation. It analyzes sales data to uncover trends, product performance, and category-level insights—designed for decision-makers and recruiters evaluating analytical depth.
Purpose
Tools & Technologies 
Tools               Purpose
SQL Server          Data Extraction & Aggregation
Excel               Dashboard Creation and Visualization
WPS Office          Initial CSV Dashboard
Dashboards Features 
* Monthly sales trend & Visualization
* Top 5 Products Revenue
* Category-wise revenue breakdown
* Interactive visuals ( line, bar, pie charts)
* Clean layout for Stakeholder readability
Statistics Analysis
Metric                     Insight
Mean Monthly Revenue       Baseline performance across months
Standard Deviation         Indicates Volatility in Sales
Top Product Contribution%  ~30% - high dependency on one SKU
Month-over-Month Growth Rate +8% steady upward trend
Z-score outliers             2 months flagged -unusually high sales
Key Techniques Used:
* Z-score for outlier detection
* Moving average for trend smoothing
* Correlation analysis ( units sold vs revenue )
* Revenue share by category for strategic targeting
Key Outcomes
Analyst Observations
* Consistent Growth: Sales show a positive trajectory with seasonal dips
* Product Concentration: One product dominates revenue, risk & opportunity
* Category Imbalance: Uneven performance across categories
* - Sales Volatility: Moderate fluctuations suggest inventory misalignment
 Business Implications
- Align inventory with top-performing months
- Diversify product focus to reduce dependency
- Target promotions around high-growth categories
- Use the dashboard for real-time decision support
 This project is a great showcase of:
• 	End-to-end analytics workflow (from SQL to dashboard)
• 	Business-oriented thinking (KPIs, trends, segmentation)
• 	Clean documentation and modular structure
• 	Readiness for client-facing analytics roles or MIS reporting
Statistical Analysis
1. Descriptive Analysis
   Total Revenue: Aggregate revenue across all months and products
→ Useful for benchmarking overall performance
• 	Mean Monthly Sales: Average revenue per month
→ Indicates baseline performance and seasonality
• 	Standard Deviation of Monthly Sales:
Measures volatility in monthly revenue
→ High SD may suggest seasonal spikes or inconsistent sales cycles
2. Trend Analysis
• 	Month-over-Month Growth Rate:
\text{Growth}_{t} = \frac{\text{Revenue}_{t} - \text{Revenue}_{t-1}}{\text{Revenue}_{t-1}} \times 100
• 	→ Highlights acceleration or deceleration in sales
• 	Moving Average (3-month):
Smooths out short-term fluctuations
→ Reveals underlying trend direction

3.  Category-Level Insights
• 	Revenue Share by Category:
\text{Category Share} = \frac{\text{Category Revenue}}{\text{Total Revenue}} \times 100
• 	→ Identifies dominant product lines
• 	Category Growth Rate:
Tracks the performance of each category over time
→ Useful for portfolio optimization

4.  Correlation Analysis (Optional)
   If additional variables like discounts, units sold, or region were available:
• 	Sales vs. Units Sold
→ Positive correlation confirms volume-driven revenue
• 	Sales vs. Discount Rate
→ Negative correlation may suggest margin erosion
5. Outlier Detection
• 	Z-score for Monthly Revenue:
Z = \frac{X - \mu}{\sigma}
• 	→ Identifies months with unusually high or low sales
• 	Box Plot Analysis (if visualized):
→ Flags outliers in product-level revenue
Business Implications
* 	Products with high revenue concentration may need diversification
*  Volatile monthly trends suggest need for inventory and marketing alignment
*  Category-level insights can guide promotional strategies
*  Statistical summaries support forecasting and budgeting decisions 
 Here are some of Questions and Answers related to the tools which I have used for doing the analysis in this project
1. What statistical measure best captures volatility in monthly sales performance?
Ans. Standard Deviation, It quantifies dispersion,helping assess sales consistency
2. A high Z-score in monthly revenue indicates:
Ans. Revenue is significantly above or below the mean, Z-Scores flag outliers, critical for anomaly detection in time series
3. Which method smooths short-term fluctuations in sales data?
Ans. Moving Average, Moving Averages reveal underlying trends by reducing noise
4.  What does the formula
\frac{\text{Revenue}_t - \text{Revenue}_{t-1}}{\text{Revenue}_{t-1}} \times 100
represent?
Ans Month-over-month growth rate. This formula calculates percentage change in revenue across months
5. What insight does “Top Product Contribution %” provide?
Ans Percentage of total revenue from the top-selling product
6.  What business implication arises from high volatility in monthly sales?
Ans Need for better inventory and marketing alignment. Volatility suggests misalignment between demands and operations.
7.  A positive correlation between units sold and revenue implies:
Ans Revenue increases with more units sold
8. Which SQL operation is best for calculating total revenue?
Ans.SELECT SUM(revenue) SUM aggregates revenue values for total computation
9.  Which Excel feature enhances dashboard interactivity for filtering by region or product?
Ans Slicer, Slicers allow dynamic filtering in dashboards
10. Which visualization best shows monthly sales trends over time?
Ans Line chart Line-charts are ideal for time-series trend analysis
Final Conclusion:
Results & Key insights
The dashboard reveals clear patterns in product performance, seasonal trends, and category-level revenue distribution. Through SQL-driven data extraction and Excel-based visualization, we identified actionable insights that support sales strategy, inventory planning, and promotional targeting.
Observed Trend what I observe in this project
Observed Trends
• 	Consistent Revenue Growth:
Month-over-month revenue shows a positive trajectory, with a few seasonal dips—suggesting strong overall sales momentum.
• 	Top Product Dominance:
One product contributes over 25–30% of total revenue, indicating high dependency and potential concentration risk.
• 	Category-Level Imbalance:
Revenue distribution across categories is uneven, with one category outperforming others by a significant margin—ideal for targeted upselling or cross-promotion.
• 	Sales Volatility:
Standard deviation in monthly revenue indicates moderate volatility, requiring tighter coordination between marketing and inventory cycles.

 Statistical Highlights 
 Metric                       Value/insight                               
 Mean Monthly Revenue         ₹X (placeholder) – baseline performance
 Standard Deviation           Indicates sales fluctuation
 Top Product Contribution%    ~30% high revenue concentration
 Month-over-Month Growth Rate +8% average-steady upward trend
 Z-score outliers             2 months flagged-unusually high sales
 Final Takeaways
  "This dashboard transforms raw sales data into strategic intelligence. It empowers decision-makers to act on trends, mitigate risks, and optimize performance—all through a clean, modular analytics workflow.”


    

    



 

  

  






   

  




