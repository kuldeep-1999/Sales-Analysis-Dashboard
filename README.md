# Sales-Analysis-Dashboard

## Problem Statement

The main objective of this project is to analyze sales data to uncover key insights that can help the business make informed decisions. Specifically, the goal is to understand sales trends, identify top-performing sub-category, and recognize customer purchasing behavior to improve future sales strategies.
![Logo](https://github.com/user-attachments/assets/e4e1952e-f8b4-478a-aef0-4a5c0bff9825)

## Overview

This project focuses on analyzing sales data using Excel. It includes various calculations, data visualizations, and insights to help understand sales trends, customer behavior, and performance metrics.

### Steps followed 

- Step 1 : Load data into Excel, dataset is a csv file.
- Step 2 : It was observed that in none of the columns errors & empty values were present.
- Step 3 : Add new columns name as Year, Month. For that use function "=Yeat" & "=Month".
- Step 4 : For calculating avergae order value, first we need order column. To create order column we need Helper column and formula is "==D2 & TEXT(A2, "yyyymmdd")". After that create a "Order ID" column and the formula is "=IF(COUNTIF($E$2:E2, E2) = 1, MAX($F$1:F1) + 1, INDEX($F$1:F1, MATCH(E2, $E$1:E1, 0)))".
- Step 5 : Create new column for profit and loss,this column show you profit and loss by using If condition "=IF([@Profit]>0,"Profit","Loss")"
- Step 6 : Create different different charts and pivot tables which helps to analysis and finding insights.
- Step 7 : Create dashboard by add all insightful charts by copy and past method.
- Step 8 : Also add filter and slicer which help to make interactive dashboard. Click any 1 chart in dashboard then click on insert and then click on slicer and then add different different slicer.
- Step 9 : To connect all chart with slicers click any 1 slicer then click on option and then click pivot table connection.

## Files:
- salesdata.csv: Contains raw sales data with various fields like customer name, product name, states, sales value, and date.
- Dashboards/Reports: Includes Excel charts and pivot tables for quick analysis and interpretation.
- Sales Insights file is also attached.

## How to Use:
- Open the Excel File: Load the salesdata.csv in Excel.
- Navigate to Sheets: Each sheet is labeled for specific analyses (e.g., "Category Sales", "Yearly Sales", "State wise Sales").
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
