# README — Kiva Loans Business Intelligence Project

## Overview

This project performs **business intelligence analysis** on the Kiva Loans dataset. It involves cleaning, exploring, and modeling the data to generate insights and predictions. The main objectives are to understand lending patterns, borrower demographics, loan distribution, and to forecast trends.

## Features

* **Data Cleaning & Preprocessing**: Handling missing values, removing duplicates, and transforming columns.
* **Exploratory Data Analysis (EDA)**: Visualizing loan amounts, repayment terms, sectors, countries, and borrower genders.
* **Machine Learning Models**:

  * **Random Forest** for predictive analysis.
  * **ARIMA** for time series forecasting.
* **Statistical Insights**: Detecting patterns in lending behavior.
* **Interactive Visualizations** (if using Jupyter Notebook or dashboard tools).

## Dataset

* **Source**: Kiva.org Loans public dataset.
* **Contents**: Information about loans including loan amount, date, borrower details, sector, and repayment schedule.
* **Format**: CSV/Excel files.

## Requirements

* Python 3.8+
* Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `statsmodels`, `jupyter` (optional).

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels jupyter
```

## Usage

1. **Open the project** in Jupyter Notebook or run the `.py` scripts.
2. **Load the dataset** (ensure the CSV file path is correct).
3. **Run the cleaning and EDA sections** to understand the data.
4. **Run modeling scripts** to get predictions and forecasts.
5. **Review visualizations** for insights.

Example run in terminal:

```bash
python kiva_analysis.py
```

## Output

* Cleaned dataset files.
* Charts showing loan distribution, top sectors, and borrower demographics.
* Predictions of loan funding likelihood (Random Forest).
* Forecast of future loan trends (ARIMA).

## Example Insights

* Countries with the highest loan activity.
* Seasonal patterns in loan requests.
* Sectors with the fastest repayment rates.

## Future Improvements

* Add a dashboard for interactive filtering.
* Use advanced NLP for borrower descriptions.
* Integrate with live Kiva API for real-time analysis.

## Author

Developed as part of a Business Intelligence course/project.
