# Project 1 – Data Cleaning & Preparation

## 📌 Project Overview

This project focuses on cleaning and preparing a raw dataset for further data analysis.

The dataset contains order-related information such as order IDs, customer IDs, products, quantities, prices, payment methods, order status, tracking numbers, coupon codes, referral sources, and total prices.

## 🎯 Objective

The main objective of this project was to:

- Identify missing or null values
- Check for duplicate records
- Correct and verify data formats
- Handle missing categorical values
- Validate numerical and date columns
- Prepare the dataset for further analysis

## 🛠️ Tools Used

- Microsoft Excel
- Python
- Pandas
- Jupyter Notebook

## 🧹 Data Cleaning Performed

### 1. Missing Value Analysis

Missing values were identified using Pandas.

The `CouponCode` column contained missing values.

The missing coupon codes were replaced with:

`No Coupon`

This prevents missing values from affecting future analysis.

### 2. Duplicate Check

The dataset was checked for complete duplicate rows.

No complete duplicate rows were found.

Individual columns were also inspected for repeated values where necessary.

### 3. Data Type Validation

The data types of the columns were checked using Pandas.

The `Date` column was verified as a datetime column, while numerical columns such as `Quantity`, `UnitPrice`, `ItemsInCart`, and `TotalPrice` were verified as numerical data.

### 4. Dataset Structure

The final cleaned dataset contains:

- 1,201 records
- 14 original data columns

Additional helper columns used during the cleaning process were excluded from the final dataset.

## 📊 Final Dataset

The cleaned dataset is provided as:

`project1_cleaned.xlsx`

The complete cleaning process is documented in:

`project1_Cleaned.ipynb`

## 🧠 Skills Demonstrated

- Data cleaning
- Missing value handling
- Duplicate detection
- Data type validation
- Excel data preparation
- Python Pandas
- Jupyter Notebook
- Basic data quality checking

## 📁 Project Files

| File | Description |
|---|---|
| `project1_Cleaned.ipynb` | Python/Jupyter Notebook containing the data cleaning process |
| `project1_cleaned.xlsx` | Final cleaned dataset |

## ✅ Project Status

Completed
