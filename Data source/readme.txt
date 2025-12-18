This CSV file contains the historical stock price data for NVIDIA, covering more than two decades of market activity. 
This dataset was sourced from Kaggle and is the foundation of the project:
https://www.kaggle.com/datasets/waqasishtiaq/nvidia

General Structure of the Dataset:
Total Records: 6,454 rows.
Total Columns: 8 variables.
Time Range: The data begins on January 3, 2000, and extends through August 2025 (based on the dataset's latest entries).

Variable Descriptions:
The dataset follows the standard financial market format known as OHLCV:
Unnamed: 0: A sequential numerical index for each record.
Unnamed: 1 (Date): The date of the trading session in YYYY-MM-DD format.
NVDA (Open): The stock price at the beginning of the trading day.
NVDA.1 (High): The highest price reached by the stock during the day.
NVDA.2 (Low): The lowest price recorded during the session.
NVDA.3 (Close): The stock price at the end of the trading day.
NVDA.4 (Adj Close): The adjusted closing price, which accounts for corporate actions such as dividends and stock splits. This is the most accurate value for long-term performance analysis.
NVDA.5 (Volume): The total number of shares traded during that day.
