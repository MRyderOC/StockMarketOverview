# USStockMarketOverview
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/MRyderOC/USStockMarketOverview/main?urlpath=voila%2Frender%2FmarketOverview.ipynb)
US Stock Market data and insights.

Understand how different sectors and industries of economy behave in stock market.

## Technologies

**Python 3.8**
#### Required libraries
- numpy
- pandas
- scipy
- matplotlib
- seaborn
- IPython
- ipywidgets
- bs4 (BeautifulSoup)
- built-in libs:
  - requests
  - datetime
  - logging

## How to use

- finviz
  * You can scrape the data using this script.
  * Find the scraped data in current directory with the current time as your file name.
- marketOverview
  * See the stock market overview to get better insights about it.
  * This notebook relies on Feb/10/2021 data.
  * To see today's overview, you should scrape the data first using finviz script then replace the new filename with the old one in the notebook. (Change cell 2)
    * You're going to see almost the same result if use another data than Feb/10. (Except the top movers of course.)

## Acknowledgments

* These scripts and notebooks were built using [finviz](https://finviz.com/) data.
* Thanks to [Mike](https://github.com/mtodisco10) who helped me with this project.
