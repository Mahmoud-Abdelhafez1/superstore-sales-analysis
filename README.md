# Superstore Sales Analysis

This project is a practical data analysis project using the **Sample Superstore 2019** dataset.

The main goal of the project is to explore sales and profit data, prepare the dataset, and identify useful business insights using Python.

## About the Project

I worked with the Superstore dataset to analyze different aspects of the business, including:

* Sales and profit performance
* Product categories and sub-categories
* Yearly and monthly sales trends
* Discounts and their relationship with profit
* Shipping time
* Sales and profit distributions
* Correlations between numerical variables
* Regional sales performance

The project focuses on applying data analysis concepts to a realistic business dataset and turning the data into meaningful insights.

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## Dataset

The project uses the **Sample Superstore 2019** dataset.

The dataset contains information about orders, customers, products, sales, discounts, profit, shipping dates, regions, and other business-related attributes.

It contains **9,994 records and 21 columns**.

## Data Preparation

Before starting the analysis, I performed several data preparation steps, including:

* Checking the dataset structure
* Checking and handling missing values
* Converting date columns to the correct format
* Checking data types
* Checking for duplicate records
* Creating new features from the order date
* Calculating shipping days
* Detecting outliers
* Optimizing memory usage where possible

Some additional features were created, such as:

* Year
* Month
* Month Name
* Day Name
* Shipping Days
* Sales Performance Category

## Analysis

The analysis focuses on several business questions, such as:

* Which categories generate the highest sales?
* Which categories generate the highest profit?
* How do sales and profit change over time?
* Which sub-categories perform better?
* How does discount relate to profit?
* How long does it usually take to ship an order?
* Which regions contribute the most to sales?
* What are the relationships between sales, profit, quantity, discount, and shipping days?

## Key Performance Indicators

Here are the main KPIs from the analysis:

| KPI              |         Value |
| ---------------- | ------------: |
| Total Sales      | $2,297,200.86 |
| Total Profit     |   $286,397.02 |
| Profit Margin    |        12.47% |
| Total Orders     |         5,009 |
| Average Discount |           16% |
| Top Category     |    Technology |

These KPIs provide a quick overview of the overall business performance.

## Key Insights

Based on the analysis, several interesting patterns were identified:

* **Technology is the strongest category**, contributing around 36.4% of total sales and generating the highest profit.

* **The West region has the largest share of sales**, accounting for approximately 31.6% of total sales.

* **Higher discounts are generally associated with lower profit**, with a negative correlation of about -0.22 between Discount and Profit.

* **Business performance improved over time**, with 2019 recording the highest annual sales and profit in the dataset.

* **High sales do not always mean high profit.** For example, Tables generated high sales but recorded a negative total profit, while Copiers achieved both strong sales and profit.

## Visualizations

Several visualizations were created using **Matplotlib** and **Seaborn** to make the analysis easier to understand.

The project includes visualizations such as:

* Sales by Category
* Profit by Category
* Sales by Year
* Profit by Year
* Sales by Month
* Profit by Month
* Sales by Region
* Sales by Sub-Category
* Profit by Sub-Category
* Profit Margin by Category
* Sales and Profit Distributions
* Average Profit by Shipping Days
* Average Profit by Discount
* Correlation Heatmap

## Outliers

Outliers were identified using the **IQR method**.

I did not automatically remove all outliers because some of them represent real business transactions with unusually high sales or profit values.

Instead, the outliers were reviewed as part of the analysis.

## Project Structure

```text
superstore-sales-analysis/
│
├── Sample - Superstore 2019.xls
├── superstore_sales_analysis.ipynb
├── README.md
└── requirements.txt
```

## How to Run

1. Clone or download this repository.
2. Make sure Python is installed.
3. Install the required libraries.
4. Open the Jupyter Notebook.
5. Run the cells from top to bottom.

Install the required libraries with:

```bash
pip install pandas numpy matplotlib seaborn jupyter xlrd
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
