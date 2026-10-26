# KC House Sales Data Understanding, Cleaning & Feature Engineering

## 1. Project Overview
This project focuses on understanding, cleaning, and performing feature engineering on the KC House Sales dataset using Python. It helps analyze house prices, identify missing values, calculate house age, and detect extreme price outliers.

## 2. Objectives
- Understand the house sales dataset.
- Identify and handle missing values.
- Handle invalid zero values in bedroom and bathroom counts.
- Convert sale dates into datetime format.
- Calculate house age and years since renovation.
- Calculate price per square foot for living area and lot size.
- Identify house price outliers using box plots and the IQR method.
- Save the cleaned dataset as a CSV file.

## 3. Dataset
**Dataset Name:** KC House Sales Dataset

**Input File:** `kc_house_data.csv`

The dataset contains house sale information, including:

- `price` – House sale price
- `bedrooms` – Number of bedrooms
- `bathrooms` – Number of bathrooms
- `sqft_living` – Living area in square feet
- `sqft_lot` – Total lot area in square feet
- `date` – House sale date
- `yr_built` – Year the house was built
- `yr_renovated` – Year the house was renovated
- `grade` – Overall construction and design grade
- `condition` – Overall condition of the house

## 4. Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

## 5. Data Cleaning
- Checked missing values in the dataset.
- Replaced zero bedroom and bathroom counts with missing values.
- Filled missing numerical values using the median.
- Removed duplicate records.
- Converted invalid sale dates and removed rows with invalid dates.

## 6. Feature Engineering
The following new features are created:

- `sale_year` – Year of the sale.
- `sale_month` – Month of the sale.
- `house_age` – Age of the house at the time of sale.
- `years_since_renovation` – Years since the last renovation.
- `price_per_sqft_living` – Price divided by living area.
- `price_per_sqft_lot` – Price divided by total lot area.

## 7. Outlier Detection
Box plots are used to visualize the distribution of house prices.

The Interquartile Range (IQR) method is used to identify potential outliers.

- Q1 = First quartile (25%)
- Q3 = Third quartile (75%)
- IQR = Q3 − Q1
- Lower Bound = Q1 − 1.5 × IQR
- Upper Bound = Q3 + 1.5 × IQR

Values outside these bounds are flagged as potential outliers. They are not automatically removed.

## 8. How to Run the Project

### Step 1: Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn
```

### Step 2: Place the Dataset

Place `kc_house_data.csv` in the same folder as your Python script or notebook.

### Step 3: Run the Code

Run the Python code in Jupyter Notebook, Google Colab, or a Python environment.

### Step 4: Check the Output

The program displays dataset information, missing values, engineered features, box plots, and outlier details.

### Step 5: Save the Cleaned Dataset

The cleaned output file is:

`cleaned_kc_house_data.csv`

## 9. Project Structure

```text
KC-House-Sales-Analysis/
│
├── kc_house_data.csv
├── house_sales_analysis.py
├── cleaned_kc_house_data.csv
└── README.md
```

## 10. Conclusion
This project demonstrates data understanding, data cleaning, feature engineering, and outlier detection using Python. The cleaned data can be used for further exploratory data analysis, visualization, and house price prediction.

## 11. Author
**Project:** House Sales Data Understanding, Cleaning & Feature Engineering

**Language:** Python
