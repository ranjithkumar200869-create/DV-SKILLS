# Healthcare Data Visualization

## Project Overview

This project is about **analyzing and visualizing healthcare data using Python**.

The main aim is to understand patient billing, medical conditions, admission patterns, and relationships between numerical data.

## Tools Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Google Colab

## Dataset

The project uses a **Healthcare Dataset**.

Important columns used are:

* Admission Date
* Discharge Date
* Medical Condition
* Billing Amount
* Gender

## Steps Performed

### 1. Load Dataset

The healthcare CSV file is loaded using Pandas.

### 2. Check Data

The dataset columns, data types, and missing values are checked.

### 3. Calculate Stay Duration

The number of days a patient stayed in the hospital is calculated using the admission and discharge dates.

### 4. Analyze Billing Amount

Billing amounts are grouped by **Medical Condition**.

Average billing amount is also calculated for each medical condition.

### 5. Create Charts

Different visualizations are created:

* Bar chart – Average billing amount by medical condition
* Violin plot – Billing amount distribution by medical condition
* Violin plot – Billing amount distribution by gender
* Line chart – Monthly patient admissions
* Heatmap – Correlation between numerical columns

### 6. Monthly Admissions

The admission month is extracted from the admission date.

The number of patients admitted each month is shown using a line chart.

### 7. Correlation Analysis

A correlation matrix is created to understand the relationship between numerical columns.

## Conclusion

This project helps to understand **healthcare data using visualization**.

It analyzes patient stay duration, billing amount, medical conditions, gender, monthly admissions, and correlations using Python charts.

## Files

* `week 6 dv(1).ipynb` – Python notebook
* `healthcare_dataset.csv` – Healthcare dataset
* `README.md` – Project documentation
