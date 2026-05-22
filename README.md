# Taiwan AQI Analysis

## Description
This project analyzes the Air Quality Index (AQI) and various pollutant levels (PM2.5, PM10, SO2) across different counties and cities in Taiwan. It comprises data cleaning pipelines, data preprocessing, normalization, and an exploratory data analysis section that visualizes the distribution, chronological trends, and seasonal variations of pollutants to assess overall air quality against recognized standards.

## Installation
1. Ensure you have Python 3.8+ installed.
2. Clone this repository.
3. Install the required Python packages:
   ```bash
   pip install pandas numpy scikit-learn matplotlib
   ```

## Usage
The analysis is broken down into three Jupyter Notebooks which should be run sequentially. You can run these inside Jupyter Lab, Jupyter Notebook, or Visual Studio Code.
1. `notebooks/01_cleaning.ipynb`: Place your original `air_quality.csv` in `data/raw/` (or update paths accordingly). Run this notebook to produce the cleaned dataset.
2. `notebooks/02_data_processing.ipynb`: Applies normalization and feature engineering.
3. `notebooks/03_visualizations.ipynb`: Generates histograms, boxplots, chronological trends, and a breakdown by city.

## Project Structure
```text
taiwan-aqi-analysis/
├── data/
│   ├── raw/                  # Original raw data (e.g., air_quality.csv)
│   └── processed/            # Intermediate and final datasets
├── notebooks/                # Jupyter Notebooks for analysis
│   ├── 01_cleaning.ipynb
│   ├── 02_data_processing.ipynb
│   └── 03_visualizations.ipynb
├── reports/                  # Generated reports and presentations
│   ├── presentation.pdf
│   └── final_report.pdf
└── README.md                 # Project overview and instructions
```