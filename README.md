# Forecasting_Mercado_Libre
Analyze the Financial and User data for Mercado Libre E-Commerce website based in Mexico. Forecast the Search Trends, Stock Price and Total Revenue to infer how well the E-Commerce company is doing and to advise the financial team on how well the website has been trending, total revenue, and investor behavior.

## Purpose
Understand trends across multiple time series to capture important times and periocity. Use date time format to leverage with Pandas tools for time periods as well with using Facebook Prophet plot_components function to plot daily, yearly, weekly, and trend of the financial and user data.
## Technology
Python
Pandas
FB Prophet
Google Colab
### Packages and Dependencies(all ran in Google Colab)
** # Install the required libraries
from IPython.display import clear_output
try:
  !pip install pystan
  !pip install fbprophet
  !pip install hvplot
  !pip install holoviews
except:
  print("Error installing libraries")
finally:
  clear_output()
  print('Libraries successfully installed')

import pandas as pd
import holoviews as hv
from fbprophet import Prophet
import hvplot.pandas
import datetime as dt
%matplotlib inline
import numpy as np

## Usage
Download Starter code
To run Facebook Prophet open a workbook in Google Colab and import the necessary files which are in Starter Code. 
Resources and forecasting_net_prophet.ipynb
Then its plug and play. Enjoy tinkering with different forecasted time frames.
