# 🍫 Chocolate Sales Data Analysis

## 📌 Project Overview

This project analyzes chocolate sales data to uncover patterns in sales performance across products, countries, and sales representatives.

The analysis demonstrates practical data analytics skills including data cleaning, exploratory data analysis, aggregation, ranking, and data visualization using Python and Pandas.

---

## 🎯 Business Problem

The objective of this analysis is to understand chocolate sales performance and identify the factors contributing to higher sales.

The analysis focuses on questions such as:

* Which chocolate products generate the highest sales?
* Which countries have the strongest sales performance?
* Which sales representatives generate the most sales?
* How do sales vary across products and markets?
* What patterns or trends can be identified from the available sales data?

---

## 📊 Dataset

The dataset contains chocolate sales transactions with information relating to:

* Sales representatives
* Countries
* Products
* Sales amounts
* Shipment/order information
* Transaction dates

The dataset was used for exploratory analysis and visualization.

> **Note:** If this dataset was obtained from a third-party source, include the original dataset/source and licensing information here.

---

## 🛠️ Tools & Technologies

* **Python**
* **Pandas**
* **Matplotlib**
* **Jupyter Notebook**
* **Microsoft Excel / Google Sheets**
* **GitHub**

---

## 🔍 Data Analysis Process

### 1. Data Exploration

The dataset was initially explored to understand:

* Number of records and columns
* Data types
* Missing values
* Duplicate records
* Unique products
* Unique countries
* Sales representatives

### 2. Data Cleaning

The data was prepared for analysis by:

* Checking for missing values
* Checking for duplicate records
* Reviewing data types
* Standardizing relevant fields
* Preparing numerical fields for analysis

### 3. Exploratory Data Analysis

The analysis examined sales performance across:

* Products
* Countries
* Sales representatives
* Orders/transactions
* Sales values

### 4. Sales Performance Analysis

Aggregations and rankings were used to identify:

* Top-selling products
* Highest-performing countries
* Top-performing sales representatives
* Sales distribution across different categories

### 5. Data Visualization

Visualizations were created to make the findings easier to interpret.

Examples include:

* Sales by product
* Sales by country
* Sales by sales representative
* Top 10 products
* Product performance comparisons

---

## 📈 Key Findings

The analysis identified differences in sales performance across products, countries, and sales representatives.

### Key insights

* **Top-performing products:** [Orange Choco]
* **Top-performing country:** [UK]
* **Top-performing sales representative:** [Brien Boise]
* **Highest sales amount:** [27990857.25]

> Replace the placeholders above with the actual results from your analysis rather than estimates.

---

## 📊 Visualizations

### Sales by Product

*Add your chart or screenshot here.*

### Sales by Country

*Add your chart or screenshot here.*

### Sales Representative Performance

*Add your chart or screenshot here.*

---

## 💻 Sample Python Analysis

```python
import pandas as pd

# Load dataset
df = pd.read_excel("Chocolate Sales.xlsx")

# Inspect the dataset
print(df.head())

# Check dataset information
print(df.info())

# Check unique products
print(df["Product"].unique())

# Calculate sales by product
product_sales = (
    df.groupby("Product")["Amount"]
    .sum()
    .sort_values(ascending=False)
)

print(product_sales)
```

---

## 📁 Repository Structure

```text
chocolate-sales-analysis/
│
├── README.md
│
├── data/
│   └── chocolate_sales.xlsx
│
├── notebooks/
│   └── chocolate_sales_analysis.ipynb
│
├── visuals/
│   ├── sales_by_product.png
│   ├── sales_by_country.png
│   └── sales_by_salesperson.png
│
└── requirements.txt
```

---

## 🚀 Skills Demonstrated

This project demonstrates practical experience with:

* Data cleaning
* Exploratory Data Analysis (EDA)
* Python
* Pandas
* Data aggregation
* GroupBy operations
* Sorting and ranking
* Data visualization
* Business-oriented data analysis
* Excel/Google Sheets
* Communicating analytical findings

---

## 📌 Conclusion

The Chocolate Sales Analysis demonstrates how sales data can be transformed into actionable business insights using Python, Pandas, spreadsheets, and data visualization.

The project provides an end-to-end example of exploring a dataset, preparing the data, analyzing sales performance, identifying patterns, and communicating findings through visualizations.

---

## 👩🏽‍💻 Author

**Delvene Ochieng**

Data Analytics | Python | Pandas | SQL | Excel | Power BI

* GitHub: [(https://github.com/delvene43-ops)]
* Portfolio: [(https://sites.google.com/view/delvene-lincky-akoth-ochieng/my-portfolio/data-analytics)]
* LinkedIn: [www.linkedin.com/in/delvenelinckyakoth]
