# python-api-challenge
Module 6
## Project Description
Project includes two programs. One (WeatherPy.ipynb) randomly selects cities from random coordinates and summarizes/plots the cities weather conditions, and creates linear regression models for sampled cities. The second one (VacationPy.ipynb) takes cities weather conditions, filters them with "good weather conditions", and plots them on a map after using an API to find the closest nearby hotel in 10km. 
## Execution
File requires to be put into folder with a folder named output_data. A file named api_keys.py should be placed with the Py files to import API keys.  
## Features
Files use the following modules: hvplot.pandas, pandas, requests, matplotlib.pyplot, numpy, datetime, time, scipy.stats, and scipy.constants. 
## Contributors
EdX code was used for almost the entire project, except for:
-Used datetime date function once to convert UNIX timestamps before analysis. <https://docs.python.org/3/library/datetime.html>
-Used convert_Temperature in both jupyter notebook files before dataframe analysis from scipy. <https://docs.scipy.org/doc/scipy/reference/generated/scipy.constants.convert_temperature.html>
## License
See License file. 