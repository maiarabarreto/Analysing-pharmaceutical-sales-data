# Drug Sales Data Analysis

## Project Overview

This project explores pharmaceutical sales data using Python, Pandas, and Matplotlib.

The main goal is to analyze medicine sales patterns over time, identify the best-selling drug categories and investigate seasonal trends in respiratory medication sales.

The project also includes a sales forecasting exercise using Linear Regression to estimate drug category sales for January 2020.

## Business Questions

The analysis aims to answer the following questions:

1. **What are the total sales quantities for each drug category (ATC code)?**
   - Identify which therapeutic categories have the highest sales volume.

2. **Which three drugs have the highest sales in January 2015, July 2016, and September 2017?**
   - Compare the best-selling drugs across three different periods.

3. **Which drug has sold the most often in 2017?**
   - Identify the drug with the highest sales quantity during 2017.

4. **Which drug category has the highest average daily sales?**
   - Calculate and compare average daily sales across ATC categories.

5. **Are respiratory drugs (R03) sold more during specific months?**
   - Investigate monthly sales patterns and identify possible seasonal trends.

## Tools and Technologies

The following tools and libraries were used:

- **Python:** Main programming language.
- **Pandas:** Data cleaning, manipulation, aggregation, and analysis.
- **Matplotlib:** Data visualization and charts.
- **Scikit-learn:** Linear Regression model for sales forecasting.
- **Google Colab:** Development environment.

## Project Methodology

The analysis follows these main steps:

1. **Data Loading:** Import the pharmaceutical sales dataset into a Pandas DataFrame.
2. **Exploratory Data Analysis (EDA):** Calculate total sales, averages, rankings, and monthly trends.
3. **Data Visualization:** Create charts using Matplotlib to identify patterns and communicate findings.
4. **Sales Forecasting:** Apply Linear Regression to estimate January 2020 sales for each drug category.

## Sales Forecasting

As an additional analysis, a Linear Regression model was developed to forecast January 2020 sales.

The model uses historical monthly sales for each drug category (ATC code) to estimate future sales.

The forecast results are compared across categories to identify which ones are expected to have the highest sales volume.

## Key Findings

- Drug category with the highest total sales: N02BE: Other analgesics and antipyretics, Pyrazolones and Anilides
- Most frequently sold drug in 2017: N02BE: Other analgesics and antipyretics, Pyrazolones and Anilides
- Drug category with the highest average daily sales: N02BE: Other analgesics and antipyretics, Pyrazolones and Anilides
- Respiratory drug sales seasonality: Respiratory drugs (R03) are sold more in the winter months
- Drug category with the highest forecast for January 2020:
  Top Forecast January 2020
  N02BE	875.308851
  R03	222.009200
  N05B	217.721025

## Repository Structure

```text
drug-sales-analysis/
│
├── data/
│   └── dataset.csv
│
├── notebooks/
│   └── drug_sales_analysis.ipynb
│
└── README.md
```

## How to Run the Project

1. Clone this repository:

```bash
git clone YOUR_REPOSITORY_URL
```

2. Open the notebook using Google Colab or Jupyter Notebook.

3. Load the dataset and run the notebook cells in order.

## Conclusion

This project demonstrates how data analysis techniques can be applied to pharmaceutical sales data to identify sales patterns, compare drug categories, investigate seasonality, and generate sales forecasts.

It also provides practical experience with data manipulation, exploratory analysis, visualization, and basic predictive modeling using Python.

---

**Author:** [Your Name]

**Project:** Drug Sales Data Analysis
