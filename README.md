# Predicting Temperatures in South Michigan 

This is a project for my Big Data class at Michigan State University. The intent of this project is to predict temperature in southern Michigan. I have collected date from the NOAA [Global Surface Summary of the Day] (https://data.nodc.noaa.gov/cgi-bin/iso?id=gov.noaa.ncdc:C00516). To get an accurate model trained, I have went back 30 years (1988-2018) across around 12 different stations including: Grand Rapids Gerald R Ford International Airport, Saint Joseph Coast Guard Station, Kalamazoo Battle Creek, Jackson Reynolds Field, Detroit Metro Airport, Belle Isle Coast Guard Station, Selfridge ANGB Train, Oakland Country International Airport, Flint FCWOS, Lansing Capital City Airport, Port Huron Coast Guard Station, and Muskegon County Airport. Below is a map that more clearly depicts the various stations that were recording the daily weather attributes. There are two data sources here. One is the folder of the separate year data files that I initially collected. The second is the weatherDataAll.csv, which is a combined data source that is sorted by date. I read in all the files and used my python notebook to create that combined data source and needed to sort by date. Checkout the python notebook for my results and my data preprocessing. Enjoy!


![](https://github.com/mswojno/weatherprediction/blob/master/weatherStationImage.png)

