# Superstore Data Analysis

## Project Overview

This project analyzes **Superstore sales data** using Python.
The main purpose is to understand the dataset, clean the data, calculate delivery time, and analyze sales by category.

## Tools Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn

## Dataset

The project uses a **Superstore CSV dataset**.

The dataset contains information related to:

* Orders
* Order Date
* Ship Date
* Category
* Sales
* Other order and sales details

## Steps Performed

### 1. Import Libraries

Pandas, NumPy, Matplotlib, and Seaborn are imported for data analysis and visualization.

### 2. Load Dataset

The Superstore CSV file is loaded using Pandas.

```python
df = pd.read_csv("samplesuperstore.csv")
```

### 3. View the Data

The first few rows are displayed using:

```python
df.head()
```

### 4. Understand the Dataset

The `info()` and `describe()` functions are used to understand the columns and statistical information.

```python
df.info()
df.describe()
```

### 5. Convert Date Columns

Order Date and Ship Date are converted into datetime format.

```python
df['Order Date'] = pd.to_datetime(df['Order Date'])
df['Ship Date'] = pd.to_datetime(df['Ship Date'])
```

### 6. Calculate Delivery Days

The number of days between order date and shipping date is calculated.

```python
df['Delivery Days'] = (df['Ship Date'] - df['Order Date']).dt.days
```

### 7. Check Categories

Unique product categories are displayed using:

```python
df['Category'].unique()
```

### 8. Check Missing Values

Missing values are checked using:

```python
df.isnull().sum()
```

### 9. Analyze Sales by Category

Total sales for each category are calculated using `groupby()`.

```python
category_sales = df.groupby('Category')['Sales'].sum()
```

### 10. Data Visualization

A bar chart is used to show **sales by category**.

A histogram is also used to show the **distribution of sales values**.

## Conclusion

This project demonstrates basic **data analysis and visualization** using Python.
The Superstore dataset is explored, date columns are processed, delivery days are calculated, missing values are checked, and sales are analyzed by category using charts.

## Files

* `superstore(1).ipynb` – Jupyter/Google Colab notebook
* `samplesuperstore.csv` – Dataset
* `README.md` – Project documentation
