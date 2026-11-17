# Data

This folder contains the raw and cleaned datasets used in the Al Rajhi Bank Stock Market Analysis (2010–2025) project.

## Files

| File | Description |
|---|---|
| `AL_Rjehei.csv` | Original raw dataset downloaded from Kaggle. |
| `AL_Rjehei_Cleaned.csv` | Cleaned and prepared dataset used for analysis in Power BI. |

## Data Source

- **Dataset:** Al Rajhi Stock Data Analysis (2010–2025)
- **Author:** Hassan Jameel Ahmed
- **Stock Ticker:** 1120.SR
- **Period:** March 2010 – December 2025
- **Original Records:** 3,926 daily trading records

**Source:** [Kaggle – Al Rajhi Stock Data Analysis (2010–2025)](https://www.kaggle.com/datasets/hassanjameelahmed/al-rajhi-stock-data-analysis-20102025)

## Data Preparation

The cleaned dataset was prepared using Microsoft Power Query in Power BI.

The preparation process included:

- Promoting the first row to column headers.
- Converting the Date column to the Date data type.
- Converting financial and trading volume columns to numeric data types.
- Reordering columns for consistency.
- Rounding numeric values to two decimal places.
- Applying a specific filtering rule to exclude records matching defined volume, closing price, and date conditions.

## Data Columns

| Column | Description |
|---|---|
| Date | Daily trading date |
| Close | Closing stock price |
| High | Highest stock price |
| Low | Lowest stock price |
| Open | Opening stock price |
| Volume | Daily trading volume |

## Notes

The original raw dataset is preserved separately from the cleaned dataset to maintain transparency and allow comparison between the source data and the prepared data.

The cleaned dataset is used as the prepared data source for the Power BI analysis.
