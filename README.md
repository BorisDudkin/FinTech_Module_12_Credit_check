# Credit Check

### Stock Price Forecast attempts to drive revenues and look into the development of Mercado Libre stock price by examining the company's Google Search traffic and aligning it with Mercado's closing prices to identify the trends and establish possible correlations.<br/>Furthermore, the application is utilizing the Facebook's developed Prophet forecast model to predict the hourly user search traffic and the firm's reveues. The trends produced by the models are analysed as well.

---

![creit](Images/credit.png)

---

## Table of contents

1. [Technologies](#technologies)
2. [Installation Guide](#installation-guide)
3. [Usage](#usage)
4. [Contributors](#contributors)
5. [License](#license)

---

## Technologies

`Python 3.9`

`Jupyter lab`

_Prerequisites_

1. `Pandas` is a Python package that provides fast, flexible, and expressive data structures designed to make working with large sets of data easy and intuitive.

   - [pandas](https://github.com/pandas-dev/pandas) - for the documentation, installation guide and dependencies.

2. `PyViz` is a Python visualization package that provides a single platform for accessing multiple visualization libraries. One of these libraries is hvPlot. <br/>

   - [PyViz ](https://pyviz.org/) - for guidance on how to start visualization, interactive visualization, styles and layouts customazation.
   - [hvPlot ](https://hvplot.holoviz.org/) is a visualization library that is designed to work with Pandas DataFrames and that we can use to create interactive plots for our data.<br/>

3. `Prophet` is a forecasting model implemented and Python. It provides completely automated forecasts and trends analysis.

   - [Facebook Prophet library ](https://facebook.github.io/prophet/) - for information on the library and its features.<br/>

---

## Installation Guide

Jupyter lab is a preferred software to work with Risk Return Analysis application.<br/> Jupyter lab is a part of the **[anaconda](https://www.anaconda.com/)** distribution package and therefore it is recommended to download **anaconda** first.<br/> Once dowloaded, run the following command in your terminal to lauch Jupyter lab:

```python
jupyter lab
```

Before using the application first install the following dependencies by using your terminal:

To install pandas run:

```python
#  PuPi
pip install pandas
```

```python
# or conda
conda install pandas
```

To install PyViz, in Terminal run:

```python
# conda
conda install -c pyviz hvplot
```

Confirm the installation of all the PyViz packages by running the following commands in Terminal type:

```python
 conda list hvplot
```

To work with Prophet library, use **[Google Colab](https://colab.research.google.com/)** (jupyter notebook in the cloud):

```
Start Google Colab at https://colab.research.google.com/
	• Choose Upload option
	• Choose File (notebook .ipynb)
Install packages in memory by !pip install pystan and !pip install prophet (this will be stored temporarily in the cloud
	• Then from lib import as usual
		○ Then from google.colab import files
		○ Upload = files.upload() to get csv files a window to upload will appear
	• Then we will just use the usual code to read from file to df
```

---

## Usage

> Application summary<br/>

Stock Price Forecast takes us through Google Search traffic analysis, Mercado Libre closing prices and the firm's revenues to establish trends and correlations as well as forecast the search traffic and revenues by utilizing Facebook's Prophet model<br/>

**Google Search and Mercado closing prices analyses:**<br/>

- Search trends in May 2020 are analysed and compared to the median monthly traffic to estimate a possible effect of revenues announcement: <br/>
  ![weekday_search](Images/av_search_weekday.png)<br/>

- Furhter breakdown is made to understand the most popular search hours during the week: <br/>
  ![popular_hours](Images/weekday_hour.png)<br/>
- Next, the weekly search trends during the year are analyzed to understand which weeks tend to be the most active in terms of Google search traffic <br/> ![popular_weeks](Images/week_of_year.png)<br/>
- The tool procedes to the stock's clsing prices analysis, starting with the trend in stock prices:<br/>
  ![mercado_closing](Images/Mercado_prices.png)<br/>
- And the closing prices are plotted next to the Search traffic to identify any common patterns::<br/>
  ![price](Images/price_trend.png)<br/>
  ![prictrende](Images/price_trend2.png)<br/>
- Mercado stock's volatility is analyzed as well:<br/>
  ![volatility](Images/stock_vol.png)<br/>
- Any possible predictable relationship between search trends and the stocks volatility and between the trends and the closing stock prices is tested via correlations between those measures::<br/>
  ![correlation](Images/vol_stock_trend_corr.png)<br/>

  **_Facebook Prophet analyses_**<br/>

- We use Prophet model to forecast the Search traffic:<br/>
  ![search_forecast](Images/fb_forecast.PNG)<br/>
- We also forecast the Search trafic 80 days into the future:<br/>
  ![search_forecasta](Images/forecast_prediction.png)<br/>
- We finalize the Search traffic analysis by looking at the trends produced by Prophet:<br/>
  ![search_trends](Images/fb_trend.PNG)<br/>
  ![fb_serach_trends](Images/fb_analysis.PNG)<br/>
- We procede with looking into the revenues figures:<br/>
  ![revenues](Images/revenues.png)<br/>
- And use Prhophet to study the revenues trends:<br/>
  ![rev_trends](Images/revenues_trends.PNG)<br/>
- We finalize our research by forecasting 90 days revenues and showing three scenarios for the revenue forecasted figures :<br/>
  ![rev_trends](Images/fb_rev_forecast.PNG)<br/>

> Getting started<br/>

- To use Portoflio Optimizer first clone the repository to your PC.<br/>
- Open `Jupyter lab` as per the instructions in the [Installation Guide](#installation-guide) to run the application.<br/>

---

## Contributors

Contact Details:

Boris Dudkin:

- [Email](boris.dudkin@gmail.com)
- [LinkedIn](www.linkedin.com/in/Boris-Dudkin)

---

## License

MIT

---
