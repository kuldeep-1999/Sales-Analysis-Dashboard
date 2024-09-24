# Sales-Analysis-Dashboard

## Overview
This project focuses on analyzing sales data using Excel. It includes various calculations, data visualizations, and insights to help understand sales trends, customer behavior, and performance metrics.

## Features:
- Data Cleaning: Handled missing values and ensured data consistency.
- Feature Engineering: Create new columns year, month by using (=YEAR),(=MONTH) function. For average order value their is no Order ID column so for that create Order ID.
  Order ID : =IF(COUNTIF($D$2:D2, D2)=1, "ORD" & TEXT(COUNTA($F$1:F1), "000"), VLOOKUP(D2, $D$1:E1, 2, FALSE)). Also create helper column drage same formula in helper column.
  
- Sales Performance Analysis: Analyzed sales trends by category, sub-category, and state.
- Visualization: Created charts and graphs to represent sales growth, product performance, and contributions.
- Summary Statistics: Included metrics like total sales, average order value, and customer retention rate.
- Actionable Insights: Identified patterns and trends to help improve sales strategy and decision-making.

## Files:
salesdata.xlsx: Contains raw sales data with various fields like product name, region, sales value, and date.
Dashboards/Reports: Includes Excel charts and pivot tables for quick analysis and interpretation.

## How to Use:
- Open the Excel File: Load the salesdata.xlsx in Excel.
- Navigate to Sheets: Each sheet is labeled for specific analyses (e.g., "Sales Overview", "Product Analysis", "Regional Performance").
- Interactivity: Use filters and slicers in pivot tables to customize your view of the data.
- Customization: Modify charts and pivot tables to suit your specific analysis needs.

## Key Learnings:
- How to clean and preprocess large datasets.
- How to visualize data in Excel using charts and pivot tables.
- How to extract insights from sales data to inform business decisions.

## Future Scope:
- Integrating more advanced Excel functions like Power Query for deeper analysis.
- Automating data refresh with macros or Excel scripting.
- Expanding analysis with additional data fields like customer demographics or marketing spend.

## Contributions:
Feel free to contribute by enhancing the data analysis techniques, adding more complex visualizations, or suggesting improvements to the overall analysis.
