# Retail Analyzer

**Retail Analyzer** is a Python-based tool for analyzing retail sales data. It provides functionalities for data loading, cleaning, filtering, calculating key metrics, and visualizing sales trends and correlations. The project uses **Pandas**, **Matplotlib**, and **Seaborn** for data manipulation and visualization.

---

## Features

1. **Load Data**
   - Load CSV files containing retail sales data.
   - Automatically detects and handles missing or malformed data.

2. **Clean Data**
   - Normalizes column names.
   - Converts dates to proper datetime format.
   - Fills missing values for price, quantity, and total sales.
   - Ensures proper data types for numeric operations.

3. **Calculate Metrics**
   - Computes total sales and average sales per transaction.
   - Identifies the most popular product based on quantity sold.

4. **Filter Data**
   - Filter data by product, category, price range, or total sale range.

5. **Display Summary**
   - Shows a summary of the dataset:
     - Total records
     - Total sales
     - Average sales per transaction
     - Most popular product
     - Sales by category

6. **Visualizations**
   - **Bar Chart**: Total sales by category.
   - **Line Chart**: Sales trend over time.
   - **Correlation Heatmap**: Correlation between price, quantity sold, and total sales.

---

## Installation

Make sure you have Python installed (version 3.7+ recommended).

Install the required libraries using pip:

```bash
pip install pandas matplotlib seaborn
