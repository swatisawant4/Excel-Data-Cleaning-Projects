# Project 01 - Financial Data Cleaning Using Power Query

## Project Overview

This project demonstrates how Power Query was used to clean and transform unstructured financial data into a structured, analysis-ready dataset.

The original dataset contained multiple financial charge components stored in a single text field. Using Power Query, these values were extracted into separate numeric columns while preserving the original raw data.

---

## Dataset Description

The dataset contains financial charge information including:

- Tax
- Interest
- Penalty
- Fees
- Others
- Total

The raw data stored all values together in one column, making analysis difficult.

---

## Problem Statement

The objective was to convert unstructured financial text into a structured dataset suitable for reporting and analysis by:

- Splitting multiple values into separate columns
- Removing currency symbols and thousand separators
- Converting text into numeric values
- Handling blank records
- Preserving valid zero-value records
- Preparing the data for dashboards and reporting

---

## Data Cleaning Steps

- Imported the dataset into Power Query
- Extracted Tax, Interest, Penalty, Fees, Others, and Total
- Removed ₹ currency symbols
- Removed thousand separators
- Converted values to Decimal Number
- Removed blank rows
- Preserved valid zero-value records
- Loaded the cleaned data into Excel

---

## Power Query Features Used

- Custom Columns
- Text.BetweenDelimiters()
- Text.Replace()
- Number.From()
- Data Type Conversion
- Remove Blank Rows
- Rename Columns

---

## Final Output

The cleaned dataset contains separate numeric columns for:

| Tax | Interest | Penalty | Fees | Others | Total |
|------|----------|----------|------|---------|-------|

The final output is clean, structured, and ready for reporting, PivotTables, and Power BI.

---

## Skills Demonstrated

- Microsoft Excel
- Power Query
- Data Cleaning
- Data Transformation
- Text Extraction
- Data Validation
- Financial Data Cleaning
- Data Preparation

---

## Project Files

- Financial_Data_Cleaning_PowerQuery.xlsx
- Raw Data
- Cleaned Data
