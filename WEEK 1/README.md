# Superstore Data Analysis

## 1. Project Overview

This project is about analyzing **Superstore sales data using Python**.

The main aim is to understand the dataset, process date information, calculate delivery days, and analyze sales based on product categories.

## 2. Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab

## 3. Dataset

The project uses the **Sample Superstore dataset**.

Important columns used in this project:

* Order Date
* Ship Date
* Category
* Sales

## 4. Data Analysis Steps

### Step 1: Import Libraries

Pandas, NumPy, Matplotlib, and Seaborn are imported for data analysis and visualization.

### Step 2: Load Dataset

The Superstore CSV file is loaded using Pandas.

### Step 3: View Dataset

The first few records are displayed using `df.head()`.

### Step 4: Understand Data

`df.info()` and `df.describe()` are used to understand the dataset and its statistical information.

### Step 5: Convert Date Columns

The **Order Date** and **Ship Date** columns are converted into datetime format.

### Step 6: Calculate Delivery Days

Delivery days are calculated by finding the difference between Ship Date and Order Date.

### Step 7: Check Categories

The unique product categories are displayed.

### Step 8: Check Missing Values

Missing values in the dataset are checked using `isnull().sum()`.

### Step 9: Calculate Sales by Category

Total sales are calculated for each category using `groupby()`.

### Step 10: Data Visualization

Two visualizations are created:

1. **Bar Chart** – Shows total sales by category.
2. **Histogram** – Shows the distribution of sales values.

## 5. Conclusion

This project demonstrates basic **data cleaning, analysis, and visualization** using Python.

The Superstore dataset is explored, date columns are processed, delivery days are calculated, missing values are checked, and sales are analyzed by category.

## 6. Project File

* `superstore(2).ipynb` – Python/Google Colab notebook
* `samplesuperstore.csv` – Superstore dataset
* `README.md` – Project documentation
