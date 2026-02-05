Exploratory Data Analysis on Synthetic Sales Data
Project Overview

This project demonstrates Exploratory Data Analysis (EDA) using a synthetic sales dataset generated with Python. The goal of the project is to understand sales patterns, regional performance, and revenue trends by applying fundamental data analysis techniques such as data cleaning, descriptive statistics, feature engineering, and visualization.

The dataset is artificially created to simulate real-world monthly sales data across multiple regions over a two-year period.

Objectives

Generate a synthetic dataset programmatically using NumPy and Pandas

Perform data cleaning and preparation

Create a new calculated feature (Average Price Per Unit)

Compute descriptive statistics (Mean, Median, Standard Deviation)

Build data visualizations using Matplotlib / Seaborn

Interpret insights from the analysis

Dataset Description

The dataset contains 24 months of sales data for 4 regions:

Column Name	Description
Month	Date of sales record
Region	Geographic sales region (North, South, East, West)
Units_Sold	Number of units sold in a month
Revenue	Total revenue generated
Avg_Price_Per_Unit	Calculated column (Revenue / Units_Sold)

Total Rows: 96
Total Columns: 5

Technologies Used

Python 3

Pandas – Data manipulation

NumPy – Data generation

Matplotlib – Visualization

Seaborn – Enhanced charts

Jupyter Notebook / Google Colab / VS Code

Steps Performed
1. Data Generation

Used numpy.random to create random sales and revenue values.

Generated 24 monthly records for each region.

2. Data Cleaning & Preparation

Ensured correct data types.

Converted Month column to datetime.

Created new feature Avg_Price_Per_Unit.

3. Descriptive Statistics

Calculated mean, median, and standard deviation.

Grouped analysis by Region to compare performance.

4. Data Visualization

Two visualizations were created:

Bar Chart – Average Units Sold by Region

Helps compare regional sales performance.

Identifies the strongest and weakest markets.

Line Plot – Monthly Revenue Trend

Shows revenue growth or decline over time.

Useful for detecting seasonal patterns or fluctuations.

Key Insights

Certain regions consistently outperform others in unit sales.

Revenue trends show fluctuations that may indicate seasonality.

Standard deviation highlights variability in sales performance.

Feature engineering (Average Price Per Unit) provides deeper pricing insight.

Project Structure
EDA-Synthetic-Sales/
│
├── eda_sales.ipynb
├── eda_sales.py
├── README.md
└── outputs/
    ├── bar_chart.png
    └── line_plot.png

How to Run the Project

Clone the repository

Install required libraries:

pip install pandas numpy matplotlib seaborn


Run the notebook or Python script:

python eda_sales.py

Conclusion

This project showcases the importance of Exploratory Data Analysis in understanding data before applying machine learning or predictive modeling. By combining statistical summaries and visual analysis, we gain meaningful insights into business performance and trends.
