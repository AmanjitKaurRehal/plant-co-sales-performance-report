  Plant Co. Sales Performance Report
    
  1. Description 
  
   Developed an interactive Power BI dashboard to analyze global plant sales and profitability by tracking YTD sales, LYTD sales, sales variance, and gross profit percentage. 
   Implemented advanced DAX calculations, data modeling, and interactive visualizations including KPI cards, treemaps, waterfall charts, combo charts, and scatter plots to deliver 
   actionable insights on country performance, product trends, and customer profitability.

 2. Technologies:

     Power BI Desktop – Built interactive dashboards and reports.
  
     Power Query (ETL) –  Cleaned, transformed, and prepared raw sales data.
   
     DAX (Data Analysis Expressions) – Created calculated measures and KPIs such as Current Year Sales,Previous Year Sales,Sales Growth/Decline,Gross Profit Percentage.These cards 
     provide executives with an immediate overview of business performance
     
     Data Modeling – Established relationships between fact and dimension tables using a star schema.The original dataset had three tables, one fact table and two dimension tables. 
    Loading the dataset into Power Query I did some minimal cleaning like removing duplicates, renaming the table, fixing the date table which for some reason was showing an error, and 
    then loading the data into power bi.
  
     Data Visualization – Designed interactive visuals including KPI cards, treemaps, waterfall charts, combo charts, scatter plots, and slicers.
        
       Treemap – Bottom 10 Countries by YTD vs PYTD Highlights countries with the lowest sales performance compared to the previous year.
                 Helps identify underperforming regions requiring business attention.
                 Allows management to investigate factors contributing to declining sales.

      Waterfall Chart – Monthly Sales Variance
       
                   Shows monthly increases and decreases in sales compared to last year.
                   Visualizes positive and negative contributions to overall performance.
                   Helps identify seasonal trends and periods of strong or weak sales.
      
       Sales Trend Analysis (Combo Chart):Displays monthly sales performance by product type:Indoor Plants,Landscape Plants,Outdoor Plants
      Combines bar and line charts to compare:Current Year Sales,Previous Year Sales.Helps evaluate product performance and sales patterns over time.

     Account Segmentation Profitability Analysis (Scatter Plot)
                 
                 Analyzes customer profitability and sales contribution.
                 
                 Each point represents a customer account.
                 
                 Enables identification of:High-sales, high-profit customers, High-sales, low-profit customers,Low-sales, low-profit customers.

                 Supports customer segmentation and strategic planning.
        
      Interactive Features
      
                 Year Slicer: Allows users to switch between different years for analysis.
                 
                 Metric Slicer: Enables users to view different performance measures such as Sales, Quantity, and Gross Profit.

                 Cross-Filtering: Selecting one visual dynamically updates other visuals.

                 Interactive Drill-Down: Facilitates deeper exploration of sales performance by country, product, and month.

   3  Data Source    
               The dataset, Plant_DTS, is an Excel file containing three key sheets:
               
                Product_Fact – Contains sales transaction details, including revenue, quantity, cost, and gross profit.
                
                Account – Stores customer account details, linking sales to specific customers.

              Datasource link : https://github.com/AmanjitKaurRehal/plant-co-sales-performance-report/blob/main/Plant_DTS.xls


  4. Key Features

            ✅ Dynamic Metric Selection – Switch between Sales, Quantity, and Gross Profit using a slicer.

            ✅ Time-Based Analysis – Compare YTD vs. PYTD performance for deep insights.

            ✅ Profitability Segmentation – Identify high- and low-performing accounts using a scatter plot (GP% vs. sales metrics).

            ✅ Bottom 20 Countries Analysis – Track underperforming countries using a Treemap visualization.

            ✅ Advanced DAX Calculations – Includes custom measures for revenue, profitability, and time comparisons.

  5. How to Use
     
            Download the dataset and open the Plant Co. Performance Report report.

            Use the metric selector to switch between Sales, Quantity, and Gross Profit.

            Adjust the year slicer to compare different time periods.

            Hover over visuals for detailed tooltips and insights.           
                
  Plant_Hierarchy – Defines the company’s location-based hierarchy for analysis.
  
   
