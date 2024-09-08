This project involves scraping stock data from websites like Nasdaq and Finviz and performing various data analysis operations on the collected data. The primary goal is to analyze financial metrics, such as Simple Moving Averages (SMA), percentage differences, net income, shares, and dividends.

# Project Overview
The project consists of two main parts:

# Data Collection: 
Using Selenium to scrape real-time stock data from Nasdaq and Finviz.
Data Analysis: Processing and analyzing the collected data using Python and pandas.
Key Features
Web Scraping: Automates the extraction of stock data such as symbols, financial metrics, and moving averages.
Data Cleaning: Handles missing or incomplete data, such as filling NaN values in the dividends column with -1.
Data Processing: Aligns rows without common columns using pandas, computes moving averages, and tracks percentage changes for each stock.
Exception Handling: Ensures each news article or stock extraction is handled individually, improving error handling during the scraping process.

# Technologies Used
Selenium: Automates browser interaction for scraping data from Nasdaq and Finviz.
Python: Core language for data manipulation and analysis.
pandas: Library for data cleaning, processing, and analysis.
XPath: Used to extract specific elements from the scraped HTML data.

# Data Analysis Operations
Simple Moving Average (SMA): Calculates short-term and long-term moving averages for each stock.
Percentage Change: Computes the daily percentage change in stock prices.
Financial Metrics: Extracts important financial data, such as net income and the number of shares.
Missing Data Handling: Fills in missing values in the Dividends column with -1.

# Future Improvements
Add more complex financial metrics (e.g., PE ratio, market cap).
Visualize stock data trends using matplotlib or seaborn.
Automate daily data scraping and analysis.

# Data Sources
Nasdaq: https://www.nasdaq.com
Finviz: https://finviz.com
CNBC: https://www.cnbc.com/world/?region=world
