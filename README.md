# COVID-19 Data Analysis

A data analysis project exploring COVID-19 trends across countries and WHO regions using Python.

## Overview

This project performs data cleaning, statistical analysis, visualization, and basic machine learning on a country-wise COVID-19 dataset to understand patterns in confirmed cases and deaths.

## Features

- Data cleaning (missing values, duplicates, outliers)
- Summary statistics by WHO region
- Distribution analysis (histograms, boxplots, Q-Q plots)
- Correlation analysis and pairwise relationships
- Hypothesis testing (t-tests, confidence intervals)
- Linear regression model for predicting deaths

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Scikit-learn

## Project Structure

    covid-analysis/
    │
    ├── data/
    │   └── Set 4-countrywise_corona.csv
    │
    ├── datathon_covid.ipynb
    ├── README.md
    └── .gitignore

## How to Run

1. Install dependencies:
```bash
pip install pandas numpy matplotlib seaborn scipy scikit-learn
```

2. Open the notebook:
```bash
jupyter notebook datathon_covid.ipynb
```

> Make sure the dataset is located in the `data/` folder as shown above.

## Output

- Cleaned dataset generated at runtime  
- Structured tables displayed in notebook  
- Visualizations (histograms, boxplots, heatmaps, pairplots)  
- Regression metrics (MSE, RMSE, R²)  

## Notes

- Dataset is included for reproducibility  
- Generated outputs are not stored in the repository  
