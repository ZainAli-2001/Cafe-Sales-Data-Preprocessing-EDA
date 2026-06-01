# ☕ Cafe Sales Data Cleaning & Exploratory Data Analysis

## Project Overview

This project focuses on cleaning, preprocessing, and analyzing a cafe sales dataset containing intentionally introduced data quality issues. The goal is to demonstrate practical data cleaning techniques, exploratory data analysis (EDA), and business insight generation using Python and Pandas.

## Dataset

**Source:**  
https://www.kaggle.com/datasets/ahmedmohamed2003/cafe-sales-dirty-data-for-cleaning-training

The dataset was designed specifically for practicing data cleaning and preprocessing workflows.

### Features

| Column | Description |
|----------|-------------|
| Transaction ID | Unique transaction identifier |
| Item | Purchased menu item |
| Quantity | Number of units purchased |
| Price Per Unit | Unit price of the item |
| Total Spent | Total transaction amount |
| Payment Method | Payment type used by the customer |
| Location | Store location |
| Transaction Date | Date of transaction |

---

## Project Objectives

- Identify and handle missing values
- Detect and resolve inconsistent records
- Perform data validation and cleaning
- Conduct exploratory data analysis
- Generate business insights from transaction data
- Visualize sales patterns and trends

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Data Cleaning Process

### Cleaning Steps Performed

- Converted data types to appropriate formats
- Parsed transaction dates into datetime format
- Handled missing values in Quantity, Price Per Unit, Total Spent, Payment Method, and Location
- Validated relationships between Quantity, Price Per Unit, and Total Spent
- Corrected missing values using business logic where possible
- Categorized unresolved missing values in Payment Method and Location as **Unknown**

---

## Exploratory Data Analysis

### Product Performance Analysis

Analyzed:

- Total quantity sold per item
- Total revenue generated per item
- Revenue contribution by product

### Time-Based Analysis

Investigated:

- Daily sales patterns
- Monthly sales trends
- Day-of-week revenue performance

### Correlation Analysis

Explored relationships between:

- Quantity
- Price Per Unit
- Total Spent

---

## Key Visualization

```text

images/daily_sales.png
images/monthly_sales.png
images/product_performance.png
```

This visualization compares:
- sales generated against days of week
- sales generated against month (for seasonality)
- product popularity (sales volume) against revenue generation.

### Insights

- Juice recorded the highest sales volume, indicating strong customer demand.
- Salad generated the highest revenue despite selling fewer units than Juice.
- Higher-priced products such as Salad, Sandwich, and Smoothie contributed disproportionately to total revenue.
- Lower-priced products such as Coffee, Tea, and Cookie achieved reasonable sales volumes but generated less revenue due to their lower unit prices.
- The most frequently purchased item was not necessarily the highest revenue-generating item.

---

## Key Findings

### Revenue Leaders

- Salad generated the highest total revenue.
- Sandwich and Smoothie were the next strongest revenue contributors.

### Most Popular Products

- Juice recorded the highest quantity sold.
- Coffee ranked second in total units sold.

### Sales Trends

- Revenue remained relatively stable throughout the year.
- June and October recorded the strongest monthly performance.
- February showed the lowest monthly sales.

---

## Project Structure

```text
project/
│
├── images/
│   ├── correlation.png
│   ├── daily_sales.png
│   ├── monthly_sales.png
|   └── product_performance.png
│
├── Cafe_Sales_Data_Cleaning_EDA.ipynb
└── dirty_cafe_sales.csv
└── README.md
```

---

## Skills Demonstrated

- Data Cleaning
- Data Validation
- Missing Value Treatment
- Exploratory Data Analysis
- Data Visualization
- Feature Engineering
- Business Insight Generation
- Pandas Data Manipulation
- Statistical Interpretation
