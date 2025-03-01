# Microsoft-Excel-Project-3

# Case study

● Jamie from Adventure Works has emailed you questions about the inventory file you are working on.

● She needs you to find the following numbers and submit them to her:

● The number of listings for gear components.

● The number of orders placed with Z123 in 2023.

● The number of orders placed with Z123 in 2022.

● The number of orders for mountain bike frames.

● The number of mountain bike orders with a stock level of over 500.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Data Filtering Process in Excel
This document outlines the step-by-step procedure for filtering data in Excel to answer various queries, using the Products worksheet as an example.

# 1. Turn on the Filter Feature
    ● Navigate to the Data tab.
    ● Click on Filter to add drop-down arrows next to each column heading.
    
# 2. Identify Gear Components
    ● Click the drop-down arrow next to the Category heading.
    ● Deselect Select All, then select Gear Components.
    ● Click OK to apply the filter
       ● The filtered data will show only Gear Components rows, hiding all others.
       ● The result will display 20 rows.
       
# 3. Clear the Filter
       ● After filtering the data, click on the Clear option in the Data tab to reset and show all rows again.
       
# 4. Filter by Supplier (Z123) for 2023 Orders
       ● Apply a filter to the Supplier column and select Z123.
       ● Then, click the drop-down arrow next to the Date Entered column and select 2023.
       ● Result: The filtered data will display 6 rows for orders placed with Z123 in 2023.
       
# 5. Filter by Supplier (Z123) for 2022 Orders
       ● Modify the Date Entered filter to select 2022.
       ● The result will now show 2 rows for orders placed with Z123 in 2022.
       
# 6. Reset Filters
       ● To reset the filters and display all rows, click the Clear button in the Data tab.
       
# 7. Filter for Mountain Bike Frames
       ● Apply a filter to the Product Name column.
       ● Use the Text Filters option and choose Contains.
       ● In the custom filter dialog, type mountain and click OK.
          ● Result: The filtered data will show 22 rows where "mountain" is part of the product name.
          
# 8. Filter Mountain Bike Orders with Stock > 500
       ● Apply a filter to the Units in Stock column.
       ● Choose Number Filters → Greater Than.
       ● Enter 500 and click OK.
           ● Result: The filtered data will display the mountain bike orders where stock is greater than 500.
       
# 9 : Key Tools and Features Used
      ● Filter by Category, Supplier, Date, Product Name, and Stock Level.
      ● Text Filters for partial matches (e.g., "mountain").
      ● Number Filters for numeric conditions (e.g., stock greater than 500).

# Conclusion
This process demonstrates how to efficiently filter and organize data in Excel based on different criteria. By using filters such as Text Filters and Number Filters, it's easier to analyze large datasets and extract valuable insights.

