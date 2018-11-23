#project1

Real Time Energy Price Forecasting
Team Members: Cris Bangaoil, Abel Kidanu, Nada Rashid

Contents:
Power Point Presentation: RT energy forecasting Presentation.pptx
	Contains the slides presented on 11/19/18

Jupyter Notebook: PJM_energy_price_forecast.ipynb
	All code to:
* Retrieve historical weather information
* Retrieve tomorrow’s forecasted weather
* Combine all data from data extracted from PJM to forecast tomorrow’s Real Time Market Hourly Prices
* Create correlation plots
* Plot forecasted data to Day Ahead pricing and actual data

PY File: config
	Contains API keys

Resources Folder (* not needed to run Jupyter Notebook)
DUQ city.csv – city names that are services by the Duquesne Light 
       Company
	DUQ Regression.csv – regression weights for our model
	Regression Analysis.doc – model summary export from Minitab
	11.14.18_da_price.csv – 11.14.18 day ahead market prices
	11.14.18_rt_price.csv – 11.14.18 actual real time market prices
	*Forecast_rt.csv – is a spit out of each real time forecast
	*ForecastWeatherData.csv – stored weather forecast data
	*WeatherData.csv – stored historical weather data
	DUQ All Data1.csv – combined data to run correlation plots

Images Folder contains plots spit out from Jupyter Notebook

Description of Research Scope – Team 8.doc: original proposal
	
