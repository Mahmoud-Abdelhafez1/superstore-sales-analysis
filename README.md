# Superstore Sales Analysis

This project is a practical data analysis project using the **Sample Superstore 2019** dataset.

The main goal of the project is to explore sales and profit data, clean and prepare the dataset, and find useful insights that can help understand the business performance.

## About the Project

I worked with the Superstore dataset to analyze different aspects of the business, including:

* Sales and profit performance
* Product categories and sub-categories
* Yearly sales trends
* Discounts and their relationship with profit
* Shipping time
* Sales and profit distributions
* Correlations between important numerical variables

The project was built using Python and focuses on applying data analysis concepts to a realistic business dataset.

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## Dataset

The project uses the **Sample Superstore 2019** dataset.

The dataset contains information about orders, customers, products, sales, discounts, profit, shipping dates, and other business-related attributes.

It contains **9,994 records and 21 columns**.

## Data Preparation

Before starting the analysis, I performed several data preparation steps, including:

* Checking the dataset structure
* Handling missing values
* Converting date columns to the correct format
* Creating new features from the order date
* Calculating shipping days
* Checking data types
* Checking for duplicate records
* Checking for outliers
* Optimizing memory usage where possible

Some additional features were created, such as:

* Year
* Month
* Month Name
* Day Name
* Shipping Days
* Sales Performance Category

## Analysis

The analysis looks at different business questions, such as:

* Which categories generate the highest sales?
* Which categories generate the highest profit?
* How do sales change over time?
* Which sub-categories perform better?
* How does discount relate to profit?
* How long does it usually take to ship an order?
* What are the relationships between sales, profit, quantity, and discount?
  
## Key Performance Indicators

Here are the main KPIs from the analysis:

| KPI | Value |
|---|---:|
| Total Sales | $2,261,536.78 |
| Total Profit | $248,940.99 |
| Profit Margin | 11.01% |
| Total Orders | 5,009 |
| Average Discount | 16% |
| Top Category | Technology |

These KPIs give a quick overview of the overall business performance.
## Visualizations

Several visualizations were created using **Matplotlib** and **Seaborn** to make the analysis easier to understand.

Examples include:

* Sales by Category
* Profit by Category
* Sales by Year
* Sub-category Performance
* Sales Distribution
* Profit Distribution
* Shipping Days Analysis
* Correlation Heatmap

## Outliers

Outliers were identified using the **IQR method**.

I did not simply remove all outliers because some of them represent real business transactions with unusually high sales or profit values.

Instead, they were analyzed as part of the dataset.

## Project Structure

```text
superstore-sales-analysis/
│
├── superstore_sales_analysis.ipynb
├── README.md
└── data/
    └── Sample - Superstore 2019.xls
```

## How to Run

1. Clone or download this repository.
2. Make sure Python is installed.
3. Install the required libraries.
4. Open the Jupyter Notebook.
5. Run the cells from top to bottom.

Install the main libraries with:

```bash
pip install pandas numpy matplotlib seaborn openpyxl jupyter
```

## What I Learned

Through this project, I practiced working with real-world data using Python.

Some of the main concepts I applied were:

* Data cleaning
* Feature engineering
* Exploratory Data Analysis (EDA)
* Data visualization
* Correlation analysis
* Outlier detection
* Basic OOP for data analysis
* Exception handling
* Memory optimization
* Exporting analysis results

## Author

**Mahmoud Mohamed Abdel Hafez Mustafa**

Data Analyst | Python | Pandas | SQL

This project is part of my journey toward becoming a professional **Data Analyst**.
