# Airline-data-analysis-using-pyspark-
"""
# Airline Data Analysis

## Introduction
This project involves the analysis of airline data spanning from 1987 to 2008. The data is sourced from multiple CSV files, and the analysis is performed using PySpark in a Databricks environment.

## Steps
1. **Data Loading**: All CSV files from the specified path are loaded into a single DataFrame.

2. **Schema Definition**: A PySpark schema is defined based on the expected structure of the data.

3. **Data Exploration**: The DataFrame is displayed, and the count of records is returned.

4. **Column Selection**: Specific columns (Origin, Dest, and Distance) are selected.

5. **Data Filtering**: Data is filtered to include only records from the year 2001.

6. **Column Removal**: The "DayofMonth" column is excluded from the DataFrame.

7. **New Column Addition**: A new column "Weekend" is created based on a condition.

8. **Column Type Casting**: The "ActualElapsedTime" column is cast to an integer type.

9. **Column Renaming**: The column "DepTime" is renamed to "DepartureTime".

10. **Duplicate Rows Removal**: Duplicate rows based on Year and Month are removed.

11. **Sorting**: The DataFrame is sorted in descending order based on the "Year" column.

12. **Data Grouping**: The data is grouped by Origin to obtain counts and by Dest to find maximum values.

13. **Data Writing**: The final DataFrame is written in Delta format.

## Conclusion
This analysis provides insights into the airline data, including trends over the years, weekend patterns, and destination information. The processed data is stored in Delta format for future use.
"""
