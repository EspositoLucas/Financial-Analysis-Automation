# Financial Analysis Automation

## Overview
This project analyzes personal banking transactions from BBVA Argentina Online Banking to gain insights into spending patterns and financial behaviors.

## Table of Contents
- Features
- Technologies Used
- Project Structure
- Installation
- Usage
- Data Processing
- Visualizations

## Features
- Transaction categorization
- Monthly expense tracking
- Spending pattern analysis
- Interactive visualizations
- Financial trend identification

## Technologies Used
- Python 3.12
- Pandas
- numpy
- panel
- hvplot
- Jupyter Notebooks

## Project Structure
```
personal-finance-analysis/
│
├── data/
│   └── transactions_2024.csv
│
├── notebooks/
│   └── money_management.ipynb
│
├── README.md
```
## Usage
1. Export your transaction data from BBVA Argentina Online Banking
2. Place the CSV file in the data directory
3. Open and run the Jupyter Notebook:
```bash
jupyter notebook notebooks/money_management.ipynb
```

## Data Processing
- Date formatting and standardization
- Transaction categorization based on description patterns
- Currency amount cleaning and conversion
- Monthly aggregation and trend analysis

## Visualizations
The project includes various visualizations:
- Monthly spending trends
- Category-wise expense distribution
- Time series analysis of spending patterns
