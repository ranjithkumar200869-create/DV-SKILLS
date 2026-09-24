# Healthcare Data Analysis

## Project Overview

This project is about **analyzing healthcare data using Python**.

The main aim is to understand the dataset, check missing values, process dates, and analyze admission and billing information.

## Tools Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Google Colab

## Dataset

The project uses a **Healthcare Dataset** in CSV format.

Some important columns are:

* Medical Condition
* Date of Admission
* Discharge Date
* Admission Type
* Billing Amount

## Steps Performed

### 1. Import Libraries

Pandas, Matplotlib, and Seaborn are imported.

### 2. Load Dataset

The healthcare CSV file is loaded using Pandas.

### 3. View Dataset

The first few rows are displayed using `head()`.

### 4. Check Dataset Information

The following are checked:

* Column names
* Number of rows and columns
* Data types

### 5. Check Missing Values

Missing values are checked using `isnull()` and `isnull().sum()`.

### 6. Convert Dates

The **Date of Admission** and **Discharge Date** columns are converted into datetime format.

### 7. Analyze Admission Type

The different admission types are counted using `value_counts()`.

The admission type values are also converted into lowercase for consistency.

### 8. Analyze Billing Amount

The `describe()` function is used to find statistical information about the **Billing Amount** column.

## Conclusion

This project helps to understand basic **healthcare data analysis using Python**.

The dataset is explored, missing values are checked, dates are processed, admission types are analyzed, and billing amount statistics are calculated.
