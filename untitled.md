# ACC102 Homework: [ AAPL Stock Price and Volume Analysis]

## 1. Project Background & Objectives
This project analyzes the daily price and volume changes of **[ (AAPL)]** from **[2023.1.1]** to **[2023.12.31]**.
The goal is to explore the relationship between price trends and trading volume using Python.

## 2. Data Source & Details
- **Data Source**: CRSP Database (`crsp.dsf` table)
- **Time Range**: `YYYY-MM-DD` to `YYYY-MM-DD`
- **Key Columns**:
  - `date`: Trading date
  - `adj_close`: Adjusted closing price (USD)
  - `vol`: Daily trading volume

## 3. Python Workflow
1.  **Data Loading**: Fetch data from CRSP via SQL queries.
2.  **Data Cleaning**: Remove missing values, check data types, and rename columns.
3.  **Data Analysis**: Calculate daily returns, moving averages, and correlation between price and volume.
4.  **Visualization**: Plot price trends, volume bar charts, and correlation heatmaps.
5.  **Interpretation**: Summarize patterns and draw conclusions from the results.

## 4. Key Findings
- **Trend**: The stock price showed an [upward/downward/volatile] trend during the period.
- **Volume Correlation**: Days with large price movements had significantly higher trading volume than average.
- **Anomalies**: A small number of missing values were found and handled using forward fill, which did not affect the overall analysis.

## 5. How to Run
1.  Install required libraries: `pandas`, `matplotlib`, `sqlalchemy`
2.  Configure your CRSP database connection
3.  Open and run the Jupyter notebook `homework.ipynb`

## 6. Limitations & Improvements
- **Limitations**: Only one stock was analyzed; macroeconomic factors were not considered.
- **Improvements**: Future work could include multi-stock comparison and benchmark index analysis.

## 7. AI Usage Statement
This project used [ChatGPT / GitHub Copilot] to assist with code comments and README structure. All core analysis, code logic, and conclusions were completed independently.