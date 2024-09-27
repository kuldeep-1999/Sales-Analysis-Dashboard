# Sales-Analysis-Dashboard

## Overview

This project focuses on analyzing sales data using Excel. It includes various calculations, data visualizations, and insights to help understand sales trends, customer behavior, and performance metrics.
Since, number of neutral/dissatisfied customers (almost 57 %) are more than satisfied customers (around 43 %), thus in all they must work on improving their services. 

### Steps followed 

- Step 1 : Load data into Excel, dataset is a csv file.
- Step 2 : It was observed that in none of the columns errors & empty values were present.
- Step 3 : Add new columns name as Year, Month. For that use function "=Yeat" & "=Month".
- Step 4 : For calculating avergae order value, first we need order column. To create order column we need Helper column and formula is "=IF(COUNTIF($D$2:D2, D2)=1, "ORD" & TEXT(COUNTA($F$1:F1), "000"), VLOOKUP(D2, $D$1:E1, 2, FALSE))"
- Step 5 : Create new column for profit and loss,this column show you profit and loss bu using If condition "=IF([@Profit]>0,"Profit","Loss")"
- Step 6 : Create different different charts and pivot tables which helps to analysis and finding insights.
- Step 7 : Create dashboard by add all insightful charts by copy and past method.
- Step 8 : Also add filter and slicer which help to make interactive dashboard. Click any 1 chart in dashboard then click on insert and then click on slicer and then add different different slicer.
- Step 9 : To connect all chart with slicers click any 1 slicer then click on option and then click pivot table connection.

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
