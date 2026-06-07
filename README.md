# Layoffs Data Cleaning Using MySQL

## Project Overview

This project focuses on cleaning and preparing a layoffs dataset using MySQL. The goal was to improve data quality and make the dataset ready for analysis.

## Skills Used

* MySQL
* Data Cleaning
* Common Table Expressions (CTEs)
* Window Functions
* ROW_NUMBER()
* Joins
* Data Standardization

## Data Cleaning Steps

### 1. Remove Duplicate Records

Used ROW_NUMBER() and window functions to identify duplicate rows and remove them.

### 2. Standardize Data

* Trimmed company names.
* Standardized industry values such as Crypto.
* Standardized country names.

### 3. Convert Data Types

Converted date values from text format to MySQL DATE format.

### 4. Handle Missing Values

* Replaced blank values with NULL.
* Filled missing industry values using existing company records.
* Removed records with insufficient information.

### 5. Final Cleanup

Removed helper columns used during the cleaning process.

## Outcome

Produced a cleaner and more consistent dataset suitable for exploratory data analysis and business insights.

