# Week 2 - Assignment: Univariate Data Analysis

**Author**: Chanin Jung  
**Course**: Introduction to Data Science  
**Data Source**: UCI Machine Learning Repository (Bike Sharing Dataset ID: 275)  

## Project Overview
This project performs an in-depth **univariate statistical analysis** on the total hourly bike rental counts (`cnt`) from the UCI Bike Sharing dataset. Reusing the data acquisition and cleaning pipeline established in Week 1, this assignment computes key summary statistics (count, min, max, mean, median, std, IQR), generates a univariate distribution plot (Histogram & Boxplot), and provides analytical conclusions.

## Project Structure
```text
week2-univariate-data-analysis/
├── data/
│   ├── raw/
│   │   └── uci_bike_sharing_raw.csv
│   ├── interim/
│   │   └── uci_bike_sharing_interim.csv
│   └── processed/
│       └── uci_bike_sharing_processed.csv
├── configs/
│   └── config.json
├── reports/
│   ├── summary_table.csv
│   └── univariate_cnt_plot.png
├── Week2_UnivariateAnalysis_ChaninJung.ipynb
├── README.md
└── .gitignore
```

## Setup & Execution
1. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn ucimlrepo jupyter
   ```
2. Open and run `Week2_UnivariateAnalysis_ChaninJung.ipynb`.
