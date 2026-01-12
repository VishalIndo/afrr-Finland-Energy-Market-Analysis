
# aFRR Energy Market & Weather Data Analysis – Finland (EU)

This repository contains a single Jupyter notebook that explores Finland’s
Automatic Frequency Restoration Reserve (aFRR) energy market using hourly market,
weather, and electricity consumption data from June 2024 to March 2025.

The notebook focuses on exploratory data analysis and a simple baseline modeling
exercise to understand relationships between demand, weather conditions, and
market-related variables.

## Contents
- Data loading and quality checks
- Exploratory data analysis (EDA) with visualizations
- Baseline linear regression model for electricity consumption
- Feature importance analysis
- Conclusion and future work discussion

## Exploratory Data Analysis Snapshot

The figure below shows pairwise relationships between selected weather variables
and electricity consumption, highlighting non-linear patterns and seasonal
effects in demand behavior.

![Pair Plot of Weather Variables and Electricity Consumption](figures/pairplot_weather_consumption.png)


## Notebook
- `01_afrr_finland_eda_baseline.ipynb`

## Data
The dataset is not included in this repository. Update the data path inside the
notebook to point to the local CSV file before running the analysis.

## Requirements
All required Python libraries are listed in `requirements.txt`.

