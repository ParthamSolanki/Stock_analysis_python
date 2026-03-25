# Stock Analysis

---

## Introduction

---

## Environment setup

### Creating environment
```Bash
mamba create -n <my_project_name> python=3.11 -y
mamba activate <project_name>
```
### Installing useful libraries
```Bash
mamba install yfinance
```

---

## [1 Eda & Cleaning](1_EDA_Cleaning.ipynb)
- Downloading 10 year ticker data.
- `auto_adjust=True` so that corporate actions like dividends, stock splits, etc. are taken care of at the source.
- Cleaning nan and 0 values as they are non trading days and are not useful for the calculations and vizualizations.
- Standardizing data types of the columns.

---

## [2 Candlestick & Moving Average](2_Candlestick_Moving_Average.ipynb)

[![Click to view Interactive Plot](Images/2_HDFC.png)](ICICIBANK.NS.html)