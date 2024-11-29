# Project Description:
  Title: E-commerce Sales Performance Analysis
  
  Objective: "Analyze sales data to identify top-performing products, high-revenue regions, and seasonal sales trends."
  
  Tools: Google Sheets, Excel, Power BI (or similar for data visualization).

# Steps for Analysis:
  
  Step 1: Data Cleaning
    
    Remove duplicates and handle missing values in all datasets.
    
    Ensure consistency in key columns for joining datasets (e.g., item_key, store_key).
  Step 2: Data Integration
    
    Join datasets using key columns:
      
      Fact Table with Item Dimension on item_key.
      
      Fact Table with Store Dimension on store_key.
      
      Fact Table with Time Dimension on time_key.
   
    Create a unified dataset for analysis.

  Step 3: Analysis by Question
    
    Question 1: Top-Performing Products
      
      Aggregate total_price by item_name to calculate revenue per product.
      
      Sort in descending order to identify top-performing products.
    
    Question 2: Revenue by Region
      
      Aggregate total_price by upazila (or higher-level regions like division) to calculate regional revenue.
      
      Visualize the results with a bar or pie chart.
    
    Question 3: Monthly Sales Trends
      
      Extract month and year from the Time Dimension.
      
      Aggregate total_price by month to find monthly sales trends.
      
      Use a line chart for visualization.

# Visualizations:
Bar Chart: Top 5 products by revenue.

Pie Chart: Revenue distribution by region.

Line Chart: Monthly sales trends over a year.
