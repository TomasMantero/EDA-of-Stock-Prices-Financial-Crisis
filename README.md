# EDA of Stock Prices - Financial Crisis

![Python](https://img.shields.io/badge/Python-3.7.6-blue) ![License](https://img.shields.io/badge/License-Apache%202.0-orange) ![Contributions](https://img.shields.io/badge/Contributions-Welcome-green)

In this notebook we analyze a dataset call [Banks Historical Stock Price](https://www.kaggle.com/tomasmantero/banks-historical-stock-price), which you can find in Kaggle.

In this notebook we will focus on exploratory data analysis of banks stock prices. We will use pandas to directly read data from Yahoo Finance. The main objective is to show step-by-step how to analyze and visualize different features from the dataset to have a better understanding of the bank industry and how it behaves.

We will focus on bank stocks and see how they progressed throughout the financial crisis all the way to early 2020.

To see the Kernel directly from Kaggle click [here.](https://www.kaggle.com/tomasmantero/eda-of-stock-prices-financial-crisis)

***Feature Columns***

* **High:** Is the highest price at which a stock traded during the course of the trading day.
* **Low:** Is the lowest price at which a stock traded during the course of the trading day.
* **Open:** Is the price at which a stock started trading when the opening bell rang.
* **Close:** Is the last price at which a stock trades during a regular trading session.
* **Volume:** Is the number of shares that changed hands during a given day.
* **Adj Close:** The adjusted closing price amends a stock's closing price to reflect that stock's value after accounting for any corporate actions. Factors in corporate actions, such as stock splits, dividends, and rights offerings.

We will get stock information for the following banks:

* Bank of America (BAC)
* CitiGroup (C)
* Goldman Sachs (GS)
* JPMorgan Chase (JPM)
* Morgan Stanley (MS)
* Wells Fargo (WFC)

About the data:

* Stock data from Jan 1st 2006 to Jan 1st 2020.
* Six banks.
* 6 columns and 3523 rows.
* Source: Yahoo Finance.

## License

This Notebook has been released under the Apache 2.0 open source license.
