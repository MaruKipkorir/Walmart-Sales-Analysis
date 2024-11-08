# Walmart-Sales-Analysis

## Overview

This project explores Walmart sales data to analyze patterns and trends across stores, dates, and external factors like holidays, temperature, fuel price, CPI, and unemployment.

## Dataset

The dataset contains 6,435 entries and includes the following columns:

- **Store**: Store ID.
- **Date**: Date of the weekly sales data.
- **Weekly_Sales**: Weekly sales figures for the store.
- **Holiday_Flag**: Indicates if the week contains a holiday (1) or not (0).
- **Temperature**: Average temperature in the region.
- **Fuel_Price**: Regional fuel price.
- **CPI**: Consumer Price Index.
- **Unemployment**: Regional unemployment rate.

## Data Overview and Cleaning

- Converted the **Date** column to a datetime format for time-based analysis.
- Verified that there were no missing values across columns, allowing for a comprehensive analysis of all records.

## Analysis and Visualizations

### 1. Descriptive Statistics

- Generated summary statistics for numerical columns, including **Weekly_Sales**, **Temperature**, **Fuel_Price**, **CPI**, and **Unemployment**.
- Counted the distribution of values in the **Holiday_Flag** column to understand the split between holiday and non-holiday weeks.

### 2. Sales on Holidays vs. Non-Holidays

- Visualized average weekly sales on holidays vs. non-holidays. Sales were generally **higher during holiday weeks**.

### 3. Sales by Store

- Calculated and visualized the average weekly sales for each store to identify high-performing and low-performing stores.

### 4. Sales Over Time

- Tracked mean weekly sales over time, plotting a time series to observe any trends.
- **Sales peak in November and December and reach their lowest levels in January and February**.

### 5. Relationship Between Sales and External Factors

- Examined relationships between weekly sales and external factors (Temperature, Fuel Price, and Unemployment) using scatter plots.
- **Temperature, Fuel Price, and Unemployment do not appear to significantly affect sales**. Initial visualizations suggest little to no correlation between these variables and weekly sales.

### 6. Additional Visualizations in Seaborn

- Used Seaborn for enhanced visualizations:
  - **Holiday vs. Non-Holiday Sales**: Bar and box plots for a detailed view of sales distribution.
  - **Sales Over Time**: Line plot of weekly sales over time.
  - **Sales by Store**: Bar plot of average weekly sales by store for an alternative view.

## Key Insights

- **Holiday Impact on Sales**: Sales are higher during holiday weeks compared to non-holiday weeks.
- **Seasonal Sales Patterns**: Sales peak in November and December, and are lowest in January and February.
- **Store Variability**: Significant differences in average weekly sales exist across stores, with some consistently outperforming others.
- **Limited Impact of External Factors**: Temperature, fuel price, and unemployment do not show any strong influence on weekly sales in this dataset.

## Conclusion

The Walmart sales data reveals meaningful insights about sales behavior in relation to holidays, time, and external economic factors. These trends could inform strategies for optimizing inventory, staffing, and promotions during different times and conditions.
