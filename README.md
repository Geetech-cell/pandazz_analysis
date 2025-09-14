# Pandas Retail Data Analysis

This project performs data cleaning, analysis, and visualization on an online retail dataset using Python, Pandas, Matplotlib, and Seaborn.

## Features

- Loads and inspects a retail CSV dataset
- Cleans data by removing missing values and duplicates
- Converts date columns to datetime format
- Computes descriptive statistics (mean, median, std)
- Groups and analyzes data by country
- Visualizes trends and distributions:
  - Monthly sales line chart
  - Top countries bar chart
  - Quantity histogram
  - Unit price vs quantity scatter plot
- Saves the cleaned dataset to a new CSV file
- Summarizes key findings

## Requirements

- Python 3.x
- pandas
- matplotlib
- seaborn

Install dependencies with:

```sh
pip install pandas matplotlib seaborn
```

## Usage

1. Place your dataset (e.g., `Online_retail.csv`) in the specified path.
2. Run the analysis script:

```sh
python pandas_analysis.py
```

3. The script will output statistics, show plots, and save a cleaned CSV.

## File Structure

- `pandas_analysis.py` — Main analysis script

## Summary of Findings

1. The dataset contained missing values and duplicates which were removed during cleaning.
2. The mean quantity sold varied significantly across different countries.
3. Seasonal trends were observed in the monthly quantity sold over time.
4. The distribution of quantity sold was right-skewed, indicating most transactions involved smaller quantities.
5. A positive correlation was observed between unit price and quantity sold, suggesting higher-priced items tended to be sold in larger quantities.

## License

MIT License
