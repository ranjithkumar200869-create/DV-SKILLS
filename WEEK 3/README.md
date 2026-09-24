# WEEK 3

## Project Title

**Apple Stock Data Analysis using Python**

## Description

This project performs a basic analysis of **Apple (AAPL) stock data** using Python.

The dataset is stored in an Excel file named `AAPL.xlsx`.

The project is performed using **Google Colab** and Python libraries.

## Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Excel Dataset

## Dataset

The dataset contains Apple stock information with the following columns:

* **Date** – Stock date
* **Open** – Opening stock price
* **High** – Highest stock price
* **Low** – Lowest stock price
* **Close** – Closing stock price
* **Adj Close** – Adjusted closing price
* **Volume** – Number of shares traded

## Steps Performed

### 1. Import Libraries

The required Python libraries are imported:

* Pandas for data handling
* NumPy for numerical operations
* Matplotlib for visualization

### 2. Upload Dataset

The `AAPL.xlsx` file is uploaded into Google Colab using the file upload option.

### 3. Read Dataset

The Excel file is loaded using Pandas:

```python
df = pd.read_excel("AAPL.xlsx")
```

### 4. Display First 5 Rows

The first five records are displayed using:

```python
df.head()
```

This helps us understand the beginning of the dataset.

### 5. Display Last 5 Rows

The last five records are displayed using:

```python
df.tail()
```

This helps us understand the end of the dataset.

## Dataset Information

The dataset contains stock market information such as:

| Column    | Description            |
| --------- | ---------------------- |
| Date      | Stock trading date     |
| Open      | Opening price          |
| High      | Highest price          |
| Low       | Lowest price           |
| Close     | Closing price          |
| Adj Close | Adjusted closing price |
| Volume    | Trading volume         |

##  Objective

The main objective of this assessment is to:

* Load an Excel dataset
* Understand the dataset
* Display the data
* Perform basic data analysis using Python
* Learn Pandas and NumPy basics
* Prepare the data for further analysis and visualization

## How to Run

1. Open **Google Colab**.
2. Upload the `.ipynb` notebook.
3. Run the cells one by one.
4. When asked, upload `AAPL.xlsx`.
5. Execute all the cells to see the results.

## Files

```text
WEEK 1 ASSESMENT (1).ipynb
AAPL.xlsx
README.md
```

## Conclusion

This project demonstrates the basic process of loading and exploring Apple stock data using Python. It provides a simple introduction to **data analysis with Pandas, NumPy, and Matplotlib**.
