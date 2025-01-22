# Encoding-Geographies-inside-UK (Customer Address and Spending Analysis Project)

This repository contains a Python project designed to analyze customer spending patterns based on their addresses. The project leverages data cleaning, transformation, analysis, and visualization techniques to uncover insights about geographical spending trends.

## Features

1. **Data Preparation**
   - Loading and inspecting customer address data (`addresses.csv`).
   - Removing missing values and duplicate entries.
   - Standardizing addresses to uppercase format for uniformity.

2. **City Mapping and Enrichment**
   - Using `cities.csv` to map customer addresses to cities.
   - Filtering out non-city entries like "England," "Scotland," etc.
   - Assigning default values to unclassified addresses.

3. **Exploratory Data Analysis (EDA)**
   - Descriptive statistics on customer spending data.
   - Identification of top and least-served cities.
   - Analysis of spending within London, outside London, and other cities.

4. **Visualization**
   - Bar charts showing total spending by city.
   - Comparisons of spending percentages across categories.
   - Insights into underserved and most-served cities.

5. **Key Metrics**
   - Total customer spend across various segments.
   - Proportion of spending in London vs. non-London cities.
   - Spending percentages for underserved and most-served cities.

## Dependencies

The project uses the following libraries:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

Install these dependencies using pip:
```bash
pip install pandas numpy matplotlib seaborn
```

## Files
addresses.csv: Input data file containing customer addresses and spending.
cities.csv: List of cities used for mapping.
Finding Cities.ipynb: Notebook for running the analysis and generating visualizations.


## Key Analysis
* Spending Breakdown
  - London vs. Non-London Spending:
    * Total spend in London.
    * Total spend outside London.
    * Spend in cities excluding "OTHER."
  - City-Level Insights:
    * Top 20 cities by spending.
    * Least-served 20 cities.
    * Proportion of underserved vs. most-served cities.
* Percent Distribution
  - Spending Proportions:
    * Percentage of total spending attributed to London.
    * Comparison of London spending to other cities, including and excluding "OTHER."
  - Underserved and Most-Served Cities:
    * Proportion of total spending for the least and most served cities.

## Visualizations
* Bar charts:
  - Top and least-served cities by total spend.
  - Percentage of spending by category (e.g., London vs. Non-London).
  - Spending comparisons for underserved vs. most-served cities.

## Sample Results
  1. Top Spending City: London has the highest customer spend
  2. Least Spending Cities: Smaller cities with minimal spending are highlighted.
  3. Spending Percentages:
    * Breakdown of total spend for key categories.
    * Insights into underserved city spending.
