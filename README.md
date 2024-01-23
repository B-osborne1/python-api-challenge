# python-api-challenge

This repo is split into 2 distinct sections, both based on the incorporation of APIs:

Section 1- WeatherPy
  This section is based on the openweather API and and citypy. The aim is to establish whether there is any correlation between latitude of cities in both hemispheres with weather conditions. Scatterplots with regression lines are used as the main source to analyse these relationships.
  The output data contains the random city generated list used, as well as global scatterplots between latitude and weather conditions (no regression on these plots).

Section 2- VacationPy
  This section uses the cities.csv file found in WeatherPy's output folder. These countries are mapped using hvplots. Following this, the dataframe is narrowed down by favourable current weather conditions before using geopify to locate destinations with close hotel accommodations. 
