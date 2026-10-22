Tech Store Sales Analysis

A data analysis project exploring technology store sales, revenue performance, advertising efficiency, customer satisfaction, and product return rates using **Python, Pandas, NumPy, and Matplotlib**.

Project Overview

This project analyzes technology store sales data to uncover useful business insights. It focuses on understanding which product categories generate the most revenue, how advertising spend relates to sales, how revenue and customer ratings change over time, and which products have the highest return rates.

The project uses data manipulation, aggregation, and visualization techniques to turn raw sales records into meaningful information that can support business decisions.

Objectives

- Analyze total revenue across product categories.
- Compare advertising expenditure with generated revenue.
- Calculate Return on Ad Spend (ROAS) to evaluate advertising efficiency.
- Examine monthly revenue and customer satisfaction trends.
- Identify products with high return rates.
- Practice exploratory data analysis (EDA) and data visualization with Python.

Technologies Used

- **Python** — data analysis and calculations.
- **Pandas** — data loading, cleaning, grouping, and aggregation.
- **NumPy** — numerical computing.
- **Matplotlib** — charts and data visualization.
- **Jupyter Notebook** — interactive analysis environment, if applicable.

Project Structure

```text
tech-store-sales-analysis/
├── project101.ipynb
├── tech_store_sales_practice.csv
└── README.md
```

*Note: Update the notebook filename above to match the actual file in your repository.*

Analysis and Visualizations

1. Data Loading and Exploration

The dataset is loaded from a CSV file, and the `Date` column is converted to a datetime format for time-based analysis.

Initial exploration uses:

- `df.info()` to inspect column types and non-null values.
- `df.describe()` to summarize numerical columns.
- `df.head()` to preview the dataset.

2. Category Revenue Performance

Sales records are grouped by product category to calculate:

- Total revenue per category.
- Average units sold per record.

A horizontal bar chart compares category revenue, making it easier to identify the strongest revenue-generating categories.

3. Advertising Efficiency — ROAS

Return on Ad Spend (ROAS) is calculated using:

**ROAS = Revenue ÷ Advertising Spend**

A scatter plot compares advertising expenditure with revenue, while color intensity represents ROAS.

This visualization helps explore the relationship between advertising spend and generated revenue.

*Note: ROAS measures revenue generated per unit of advertising spend; it is not the same as profit or net ROI.*

4. Monthly Revenue and Customer Ratings

Sales data is aggregated by month to examine:

- Total monthly revenue.
- Average monthly customer rating.

A dual-axis line chart visualizes both metrics over time, helping reveal trends and potential relationships between sales performance and customer satisfaction.

5. Product Return Rate Analysis

Product-level summaries calculate:

- Total units sold.
- Total revenue.
- Average customer rating.
- Total returned units.
- Return rate as a percentage.

The return rate is calculated as:

**Return Rate (%) = (Returned Units ÷ Units Sold) × 100**

Products are sorted by return rate in descending order to highlight those with the highest observed return percentages.

Key Business Questions

This analysis is designed to help answer questions such as:

1. Which product categories generate the most revenue?
2. How does advertising spend relate to revenue?
3. Which sales records show stronger ROAS?
4. How do revenue and customer ratings evolve over time?
5. Which products have the highest return rates?
6. Which products may deserve further investigation based on sales, customer ratings, and returns?

Actual findings should be documented after examining the generated charts and summary tables.

Getting Started

Prerequisites

Install Python and the required libraries:

```bash
pip install pandas numpy matplotlib jupyter


Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/Abdurrahman-byte/tech-store-sales-data-analysis.git
   ```

2. Navigate to the project directory:

   ```bash
   cd YOUR-REPOSITORY
   

3. Ensure `tech_store_sales_practice.csv` is available in the expected location.

4. Launch Jupyter Notebook:

   ```bash
   jupyter notebook

5. Open the analysis notebook and run the cells sequentially.

Replace `Abdurrahman-byte` and `tech-store-sales-data-analysis` with your actual GitHub details.

Dataset Requirements

The analysis expects a CSV file named `tech_store_sales_practice.csv` containing these columns:

| Column | Description |
|---|---|
| `Date` | Date associated with a sales record |
| `Category` | Product category |
| `Product` | Product name |
| `Revenue_USD` | Revenue in US dollars |
| `Units_Sold` | Number of units sold |
| `Ad_Spend_USD` | Advertising expenditure in US dollars |
| `Customer_Rating` | Customer rating |
| `Returned_Units` | Number of returned units |

The dataset should contain valid numerical values for the calculations. Missing values, zero advertising spend, and products with zero units sold should be handled appropriately before interpreting the results.

Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Data loading and preprocessing
- Datetime conversion and monthly aggregation
- Grouping and aggregation with Pandas
- Business metric calculation
- Advertising performance analysis
- Product return analysis
- Data visualization with Matplotlib
- Communicating data-driven business questions

Future Improvements

Potential extensions include:

- Add interactive dashboards using Plotly or Streamlit.
- Investigate sales trends by product and category.
- Compare return rates with customer ratings.
- Add profit and cost analysis if the necessary data becomes available.
- Handle missing values and zero denominators explicitly.
- Build a concise business report with verified findings and recommendations.

Author

**Abdurrahman**

Aspiring AI/ML Engineer exploring Python, data analysis, and practical applications of machine learning.



*This project is part of my ongoing journey toward building practical, data-driven software and AI solutions.*
