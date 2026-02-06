## Trader-Performance-vs-Market-Sentiment

# Project Overview
This project analyzes the relationship between market sentiment (via the Fear and Greed Index) and individual trader behavior. By merging historical trade data with daily sentiment values, this analysis seeks to understand how market emotions influence trading frequency, position sizing, and profitability.

# Setup & Prerequisites
You will need the following Python libraries, which are imported at the beginning of the notebook:
pandas for data manipulation, numpy (Numerical operations), matplotlib (Basic plotting), seaborn (Statistical data visualization)

# Data Requirements
The notebook requires two specific CSV files to be present in the same directory:
fear_greed_index.csv: Contains historical sentiment data with columns like timestamp, value, classification, and date.
historical_data.csv: Contains raw trade data including Account, Closed PnL, Size USD, Side, and Timestamp IST.

# How to Run
Clone/Download this repository or download the Round0Assignment.ipynb file.
Place the required data files (fear_greed_index.csv and historical_data.csv) in the root folder.
Launch Jupyter Notebook or JupyterLab.
Open Round0Assignment.ipynb and run all cells sequentially.
