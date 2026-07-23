#  - Data Cleaning using Python

## Project Overview

This project demonstrates professional data cleaning techniques using Python, Pandas, and NumPy. A deliberately messy dataset was cleaned and transformed into an analysis-ready dataset by handling missing values, removing duplicates, standardizing data, detecting outliers, correcting data types, and generating a data quality report.

## Objective

The objective of this project is to improve the quality of raw data by performing systematic data cleaning and documenting every step of the process.

## Tech Stack

- Python
- Pandas
- NumPy
- Jupyter Notebook

## Dataset Information

- Dataset Name: dirty_data.csv
- Total Rows: 823
- Total Columns: 16

## Data Cleaning Tasks Performed

### 1. Data Loading
- Imported the dataset using Pandas.
- Explored the dataset using `head()`, `info()`, and `describe()`.

### 2. Data Quality Report
- Identified missing values in each column.
- Checked duplicate records.
- Verified data types.
- Examined value ranges for numerical columns.

### 3. Missing Value Handling
- Filled missing values in numerical columns with **0**.
- Justification: Missing values represent the absence of transactions or records for specific shipping modes.

### 4. Duplicate Removal
- Checked for duplicate rows.
- Removed duplicate records if found.

### 5. Data Standardization
- Converted column names to lowercase.
- Replaced spaces with underscores.
- Removed unnecessary spaces.
- Converted `Order ID` to string data type.

### 6. Outlier Detection
- Detected outliers using the **Interquartile Range (IQR)** method.
- Capped extreme values instead of removing them to preserve dataset size.

### 7. Data Type Correction
- Verified that all columns have appropriate data types.
- Ensured `Order ID` is stored as a string.

### 8. Before vs After Summary
Compared dataset quality before and after cleaning:
- Row count
- Duplicate count
- Missing values
- Data types

### 9. Export Cleaned Dataset
- Saved the cleaned dataset as:

```
cleaned_dataset.csv
```

## Project Structure

```
Task-3-Data-Cleaning/
│
├── dirty_data.csv
├── cleaned_dataset.csv
├── Data_Cleaning.ipynb
├── README.md
```

## Libraries Used

```python
import pandas as pd
import numpy as np
```

## Output

The cleaned dataset is ready for further data analysis, visualization, and machine learning applications.

## Learning Outcomes

- Data Quality Assessment
- Missing Value Treatment
- Duplicate Removal
- Data Standardization
- Outlier Detection using IQR
- Data Type Correction
- Dataset Export
- Professional Documentation

## Author

**Nikhitha Neelam**

B.Tech - Computer Science and Engineering

Data Analytics Intern
