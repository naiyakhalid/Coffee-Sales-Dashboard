# Coffee-Sales-Dashboard
This project provides a comprehensive overview of sales performance across time, countries, and customer segments. It visualizes trends by coffee type, highlights top-performing countries and customers, and offers filters by roast type, loyalty card status, and product size for deeper analysis.

## Link of the Dataset: 
- <a href= "coffee-Orders-Dataset.xlsx">Coffee sales Dataset</a>

## KPIs for Your Bike Sales Dashboard Project
__1. Total Sales Revenue__
- Measures the overall revenue generated from coffee sales.
- __Example__ (from dashboard): ~$45,133.4 (sum of sales across countries shown).
  
__2. Sales by Country__
- Compares performance across different regions.
- __Example KPIs:__
- United States: $35,638.9
- Ireland: $6,696.9
- United Kingdom: $2,798.5
  
__3. Top 5 Customers by Revenue__
- Identifies the highest-value customers.
__Example:__
- Allis Wilmore: $317.1
- Brenn Dundredge: $307.0
- Terri Farra: $289.1
  
__4. Sales Trend Over Time__
- Tracks monthly sales performance to identify seasonal trends or spikes.
- Can be used to calculate: Average monthly sales, Best and worst performing months
  
__5. Sales by Coffee Type__
- Tracks performance by product variety (Arabica, Robusta, Excelsa, etc.)
- KPI: Sales distribution per type over time

__6. Roast Type Popularity__
- Measures which roast types (Dark, Medium, Light) contribute most to sales.
  
__7. Loyalty Program Impact__
- Compares sales from customers with and without loyalty cards.
- KPI: % of sales from loyalty card holders.
  
__8. Sales by Size__
- Breaks down performance by packaging size (e.g., 0.2 kg, 0.5 kg, 1.0 kg, 2.5 kg)

# Process of Creating the Coffee Sales Dashboard:
- Verify data for any missing values and anomalies, and sort out the same.
-  Made sure data is consistent and clean with respect to data type, data format and values used.
- Used XLOOKUP to populate customer details (e.g., Customer Name, Email) in the orders table by referencing the Customers sheet.
- Used INDEX and MATCH functions to batch-fill product-related columns such as Coffee Type, Roast Type, Size, and Unit Price in the orders table from the Products sheet.
- Created two new columns — Coffee Type Name and Roast Type Name — to expand abbreviations into full names for better clarity and to avoid confusion.
- Added a Loyalty Card column in the orders table and used XLOOKUP to retrieve loyalty status from the Customers table.
- __Applied formatting:__
  Added dollar signs to price-related columns for clear monetary representation.
  Added "kg" unit to the Size column to represent packaging weight clearly.
- Created multiple Pivot Tables to answer specific analytical questions.
- Combined all pivot tables into a single interactive dashboard using slicers for fields like Roast Type, Loyalty Card, and Size to enable dynamic filtering.
- Added a timeline slicer to visualize and filter monthly sales data from 2019 to 2022.



