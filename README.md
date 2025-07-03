# Coffee_Sales_Dashboard_in_Excel

Performed analysis on 1000 entries of coffee sales data from 2019 to 2022 and visualized it in an interactive dashboard. My analysis includes: 
- Total Sales Over Time
- Sales by Country
- Top 5 Customers

These visualizations can be filtered by:
- Time
- Coffee Roast Type: Dark, Light, Medium
- Size: 0.2kg, 0.5kg, 1.0kg, and 2.5kg
- Loyalty Card: Yes, No

My analysis workflow: 
1. Format data
   - Replace abbreviated fields with full fields using nested if functions (Example: Roast Type: M, L, D -> Medium, Light, Dark)
   - Change Unit Price and Sales to Currency data type
2. Populate the main data sheet with information about the customer and their order using XLOOPUP, INDEX & MATCH
3. Turn the data into a table
4. Perform analysis on the data by creating pivot tables and pivot charts
5. Create a new sheet for the dashboard
   - Copy all pivot charts from other sheets and paste it in this new sheet
   - Create a title bar for the dashbaord
   - Create slicers to make the dahsboard interactive
   - Organize slicers and graphs to complete the dashboard
  
   
