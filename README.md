# Walmart Sales Performance: Trends, Seasonality & Forecasts Dashboard

## Project Overview
This Power BI dashboard analyzes Walmart sales data from 2010 to 2012, showcasing revenue trends, seasonality patterns, holiday impacts, and sales forecasting for the next 2 years (2013-2014). The dashboard provides insights into store and department performance, enabling data-driven decisions for sales optimization and inventory planning.

### Objectives
- Analyze historical sales trends and seasonality from 2010 to 2012.
- Forecast future sales for 2013-2014 to support strategic planning.
- Evaluate the impact of holidays on sales performance.
- Identify top-performing departments and stores and which month generates more sales
- Offer interactive filtering for store and department-level analysis.

## Tools Used
- **Power BI Desktop** for data visualization and analysis.
- **Dataset:** Custom CSV file (`Walmart_Sales_Forecasting`) containing weekly sales details.

### Visualizations
- **KPI Card: Total Sales**
  - Displays total sales: **6.74 billion**.
- **Line Chart: Total Sales Forecasting Over the Next 2 Years**
  - Shows revenue trends from 2010 (peak at 2.45B) to 2012 (2.00B), with a forecast extending to 2014.
- **Bar Chart: Avg Sales by Category (Holiday vs. Non-Holiday)**
  - Compares average sales: Holiday weeks (**17.0K**) vs. Non-Holiday weeks (**15.9K**).
- **Scatter Plot: Total Sales by Months**
  - Visualizes monthly sales, highlighting seasonality (e.g., peaks in April/July at 0.65B).
- **Bar Chart: Top 5 Departments with the Most Sales**
  - Identifies top departments: 38,72,90,92,95 
- **Histogram: Sales Performance Across Stores**
  - Shows sales distribution, with top stores reaching 0.3B and most below 0.1B.
- **Slicers: Store and Department**
  - Interactive filters for selecting specific stores (e.g., All) and departments (e.g., 1 to 99).

## Insights
- **Overall Sales Performance:**
  - Total sales amount to **6.74 billion** across 2010-2012, with dynamic updates based on store and department filters.
- **Sales Trends and Forecast:**
  - Sales peaked in 2011 at **2.45 billion**, declining to **2.00 billion** by 2012, with a forecasted continued decline into 2014.
  - Seasonal spikes occur in April/July 
- **Holiday Impact:**
  - Holiday weeks generate an average of **17.0K**, a **6.9% increase** over non-holiday weeks (**15.9K**), highlighting the importance of holiday planning.
- **Seasonality Patterns:**
  - Sales peaks in April/July (0.65B) and dips in January/November, suggesting a need for targeted inventory adjustments.
- **Store Performance:**
  - Sales are uneven, with top stores hitting **0.3 billion** while most are below **0.1 billion**, suggesting variability in location or management effectiveness.

## Screenshots
![image](https://github.com/user-attachments/assets/364ab53d-3e6f-4955-9ce8-9115b68a65c0)

## Files
- **Walmart_Sales_Forecasting.pbix:** Power BI file containing the interactive dashboard.
- **Walmart_Sales_Forecasting.csv** Source dataset with weekly sales details.
- **walmart_sales_dashboard.png:** Visual representation of the dashboard.
- **README.md:** This documentation file.

 **Interacting with the Dashboard:**
   - Use the **Store** and **Department** slicers to filter data (e.g., select a specific store or department).
   - Explore the line chart for historical trends and forecasts.
   - Analyze bar charts and scatter plots to identify seasonality, holiday impacts, and top performers.

## Project by
**Javier Tay Yu Xiang**  
[Year 2 Economics and Data Science Student, NTU]  
[Aspiring Data Analyst]  
(https://www.linkedin.com/in/javier-tay-a89a3b202/)

## Acknowledgments
- Dataset inspired by the Walmart Sales Forecasting competition on Kaggle.
- Guidance from Power BI tutorials and DAX advice.

## Limitations
- **Data Range:** Limited to 2010-2012, affecting long-term forecast accuracy.
- **Missing Visuals:** Year-over-year growth (calculated via DAX) is not visualized but can be added as a waterfall chart.
- **Granularity:** Forecast is at a yearly level; monthly forecasts could enhance precision.

## Future Improvements
- Add a waterfall chart to visualize year-over-year sales growth in percentage terms.
- Incorporate additional DAX measures (e.g., cumulative sales, weekly sales change %).
- Extend forecast granularity to monthly predictions for better planning.
- Analyze external factors (e.g., economic conditions, store locations) to explain trends.
