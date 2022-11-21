# Stock Sentiment Word Cloud
Application that allows users to input a stock ticker and generate a word cloud of the sentinments around the stock. 

--- 

## Technologies

This project leverages Python 3.7 and Jupyter Lab with the following packages:

* [Pandas] (https://github.com/pandas-dev/pandas) - To create and manipulate dataframes
* [NewsAPI] (https://newsapi.org/) - To pull news data
* [NLTK] (https://github.com/nltk/nltk) - To clean and generate wordcloud from news data
* [Wordcloud] (https://github.com/amueller/word_cloud) - Used to generate final wordcloud display
* [Tradingview-TA] (https://github.com/brian-the-dev/python-tradingview-ta) - For market sentiment & recommendations from Tradingview
* [Matplotlib] (https://github.com/matplotlib/matplotlib) - Used to generate final wordcloud display

(Import code blocks included in application)

--- 

## Installation Guide

Before running the application, first install the following dependencies 

```python
  pip install pandas
  pip install yfinance
  pip install tradingview_ta
  pip install --upgrade mplfinance
  pip install hvplot
  
```

And get API key from newsapi.org

---

## Examples

Upon running the inital code for yfinance data, you will asked to input a stock ticker for data.

![Yfinance Data Prompt](Images/Yfinance_Data.PNG)

Input in the following format 

![Yfinance Data Prompt Complete](Images/Yfinance_Data2.PNG)



The following code will display a candlestick chart with 8/13/21 EMA's, ADX, and Volume. Must run all code blocks beforehand for this to display properly.

![Candlestick Created](Images/Candlestick_Display.PNG)




---

## Usage

To use the Algo Trading Project application, clone the repository and run the **Backtest Trade Algorithm.ipynb** on Jupyter Lab. 

Currently does not connect to brokerages, however the entry signals can be used to take trades manually.



