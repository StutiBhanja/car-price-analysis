# Car Price Analysis 🚗

## Overview
Comprehensive Exploratory Data Analysis (EDA) on a dataset of 205 cars with 26 features to identify key price determinants.

## Tools Used
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-blue?style=flat)
![Seaborn](https://img.shields.io/badge/Seaborn-teal?style=flat)

## Dataset
- 205 cars with 26 features
- Source: Kaggle

## Key Findings
| Feature | Correlation | Strength |
|---------|-------------|----------|
| Engine Size | r = 0.87 | Very Strong ✅ |
| Curb Weight | r = 0.84 | Very Strong ✅ |
| Horsepower | r = 0.81 | Very Strong ✅ |
| City MPG | r = -0.69 | Strong Negative ❌ |

## Analysis Performed
- ✅ Data cleaning — fixed 5 brand name typos
- ✅ Outlier analysis — retained 15 luxury cars above $30K
- ✅ Univariate analysis — histograms, KDE plots, boxplots
- ✅ Bivariate analysis — scatter plots, correlation heatmap
- ✅ Pivot table analysis

## Files
| File | Description |
|------|-------------|
| `Car_Price_Analysis_EDA.ipynb` | Main analysis notebook |
| `CarPrice_Assignment.csv` | Dataset |
