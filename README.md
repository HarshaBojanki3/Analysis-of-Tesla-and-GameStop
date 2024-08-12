# Analysis of Tesla and GameStop

This project analyzes the stock prices and quarterly revenue data of Tesla (TSLA) and GameStop (GME). The analysis is performed using Python in a Jupyter Notebook, with data fetched via the `yfinance` library and web scraping techniques.

## Project Overview

This analysis covers the following key steps:
1. **Data Retrieval**:
    - Use `yfinance` to fetch historical stock data for Tesla and GameStop.
    - Web scraping to extract quarterly revenue data for both companies.

2. **Data Processing**:
    - Cleaning and preparing the data for analysis, including resetting indices and converting date formats.

3. **Data Visualization**:
    - Generate visualizations comparing stock prices and revenue over time to observe trends and anomalies.

## Files in this Repository

- `Analysis of Tesla and GameStop.ipynb`: The Jupyter Notebook containing all the code and analysis.
- `README.md`: This file, providing an overview of the project.

## Prerequisites

To run this notebook, you'll need to have the following installed:
- Python 3.x
- Jupyter Notebook
- Required Python libraries: `yfinance`, `pandas`, `matplotlib`, `beautifulsoup4`, `requests`

You can install the required libraries using pip:

```bash
pip install yfinance pandas matplotlib beautifulsoup4 requests
