# Number-of-Bikes-Rented

## Introduction

This is a linear regression, decision tree regression and random forest regression project that predicts the number of bikes that will be rented using a dataset containing historical data detailing weather, time and seasons at hourly basis.

## Data

The Dataset contains information under various column heads which are explained below:

- instant: record index
- dteday : date
- season : season (1:springer, 2:summer, 3:fall, 4:winter)
- yr : year (0: 2011, 1:2012)
- mnth : month ( 1 to 12)
- hr : hour (0 to 23)
- holiday : weather day is holiday or not (extracted from [Web Link])
- weekday : day of the week
- workingday : if day is neither weekend nor holiday is 1, otherwise is 0.
- weathersit : 1: Clear, Few clouds, Partly cloudy, Partly cloudy
               2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
               3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
               4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
- temp : Normalized temperature in Celsius. The values are derived via (t-t_min)/(t_max-t_min), t_min=-8, t_max=+39 (only in hourly scale)
- atemp: Normalized feeling temperature in Celsius. The values are derived via (t-t_min)/(t_max-t_min), t_min=-16, t_max=+50 (only in hourly scale)
- hum: Normalized humidity. The values are divided to 100 (max)
- windspeed: Normalized wind speed. The values are divided to 67 (max)
- casual: count of casual users
- registered: count of registered users
- cnt: count of total rental bikes including both casual and registered

The data is present in the repository in a CSV format or else can be downloaded from [here](https://archive.ics.uci.edu/ml/datasets/bike+sharing+dataset).

# Requirements

The project was done in Jupyter Notebook, Python 3.
