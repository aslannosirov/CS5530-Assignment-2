# Part 1
This project performs data cleaning, preprocessing, and basic data manipulation on a used-car dataset containing 5,847 rows and multiple car attributes. The goal is to prepare the data for further analysis and modeling.

Steps Completed
1. Data Loading
Imported the raw dataset into Python using pandas.
2. Missing Value Analysis
Identified missing values across all columns.
Columns with very few missing values (Mileage, Engine, Power, Seats) were imputed.
Columns with extremely high missing percentage (e.g., New_Price with 86% missing) were removed.
3. Data Cleaning
Removed units from numeric columns:
Mileage (removing “kmpl”, “km/kg”)
Engine (removing “CC”)
Power (removing “bhp”)
New_Price (removing “Lakh”)
Converted all cleaned values to numerical format.
4. Imputation
Numeric columns: filled missing values using median.
Categorical-like columns (Seats): filled using mode.
5. Feature Engineering
Created a new feature: Car_Age = 2025 − Year.
6. Encoding Categorical Variable
Converted Fuel_Type and Transmission into one-hot encoded variables.
7. Data Manipulation
Select (choosing specific columns)
Filter (subset rows by conditions)
Rename (renaming columns)
Mutate (creating new columns)
Arrange (sorting data)
Group By + Summarize (aggregating by categories)

8. Saving the Processed Dataset
Exported the cleaned data to a new CSV (cleaned_used_cars) file for further analysis
