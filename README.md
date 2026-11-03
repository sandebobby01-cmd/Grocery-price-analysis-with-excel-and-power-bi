# Grocery Price Analysis | Excel & Power BI
Power BI dashboard comparing grocery prices across Walmart, Target, and Costco.
## Approach

I imported the Excel dataset into Power BI and prepared it for analysis.

 ### Data Cleaning and Preparation

- Converted the Price column to Decimal Number and displayed prices with two decimal places.
- Converted the Date column to a date data type.
- Used the Store, Product, Price, and Date fields to compare recorded prices.
- Created column charts to show price differences by product and total recorded prices by store.
- Added data labels and consistent store colours to improve readability.
- 
## Excel Analysis

I used the same grocery dataset to build an interactive Excel analysis comparing Walmart, Target, and Costco.

### PivotTable
- Placed Store in Rows and Product in Columns.
- Summarised Price using Sum to compare total recorded prices.
- Formatted the values as currency with two decimal places.

### PivotChart
- Created a clustered column PivotChart to compare recorded prices across stores and products.
- Used different colours to distinguish product categories.

### Slicers
- Added Product, Date, and Store slicers for interactive filtering.
- Users can select specific products, dates, or stores to explore the results.

## Main Findings

Across all recorded dates:
- Costco had the lowest overall total: 219.92.
- Target's total was 229.42, while Walmart's was 234.55.
- Costco had the lowest totals for bottled water and dried beans.
- Target had the lowest totals for rice and canned vegetables.
- Walmart had the lowest total for milk.

These figures sum recorded prices across multiple dates; they do not represent a single shopping basket.

## Excel Preview

![Excel PivotTable, PivotChart, and slicers](<Excel Pivot grocesry analysis.png>)

[Download the Excel workbook](grocery_price_analysis_excel.xlsx)
