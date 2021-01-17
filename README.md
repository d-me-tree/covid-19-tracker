# LiveProject: Build a COVID-19 Tracker with Time Series Analysis

## Datasets

You can directly use the raw files from [GitHub](https://github.com/CSSEGISandData/COVID-19):

- [Confirmed Global Cases](https://github.com/CSSEGISandData/COVID-19/blob/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_confirmed_global.csv): time series data for forecasting
- [Number of Death Cases - Global](https://github.com/CSSEGISandData/COVID-19/blob/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_deaths_global.csv): time series data for deaths
- [Number of recovered cases - Global](https://github.com/CSSEGISandData/COVID-19/blob/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_recovered_global.csv): time series data for recovered cases
- [US Confirmed Cases](https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_confirmed_US.csv): us_confirmed_df
- [US Death Cases](https://github.com/CSSEGISandData/COVID-19/blob/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_deaths_US.csv): us_death_df
- [Country-specific Data](https://raw.githubusercontent.com/CSSEGISandData/COVID-19/web-data/data/cases_country.csv): to analyze the current global scenario.

This dataset contains daily time series summary tables, including confirmed, deaths, and recovered cases. All data is read in from the daily case report. The time series tables are subject to be updated if inaccuracies are identified in our historical data. The daily reports will not be adjusted in these instances to maintain a record of raw data.

#### Data for time series forecasting

Three time series tables are for the global confirmed cases, recovered cases, and deaths. Australia, Canada, and China are reported at the province/state level.

Dependencies of the Netherlands, the United Kingdom, France, and Denmark are listed under the province/state level. The United States and other countries are at the country level. The tables are named  `time_series_covid19_confirmed_global.csv` and  `time_series_covid19_deaths_global.csv`, and  `time_series_covid19_recovered_global.csv`, respectively.
