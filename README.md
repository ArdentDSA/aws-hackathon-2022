# Ardent DSA Team Entry for AWS Disaster Response Hackathon

Collaborative project of the Ardent DSA team to build a ML model and compete in the 2022 AWS Hackathon

## Description

We built an XGBoost model to predict the severity of wildfires in California using historic wildfire and weather data.  We focused on California wildfires that occurred between January 1, 2000 through December 31, 2015 in the following counties: Riverside, Los Angeles, El Dorado, San Bernardino, and San Diego.  Daily measures of average precipitation, temperature, and wind speed were coupled with the wildfire data.


## Authors

Contributors names

* Katherine Kelso
* Michael MacMahon
* Erin Pineda
* Andrew Terrell
* Jon Zimmerman

## Challenges
* Finding a reliable dataset
* Cleaning the dataset sufficently
* Deciding on a methodology for analysis
* Tinkering with final methodology to improve results


## Outcomes
* Model achieved a MAE of 87
* Feature importance revealed most influential factors in model: average wind speed, length of fire (in days), average temperature, the year 2007, and the month of October.



## Acknowledgments

Data obtained from these sources:
* [1.88 Million US Wildfires](https://www.kaggle.com/rtatman/188-million-us-wildfires)
* [NOAA Physical Sciences Laboratory](https://psl.noaa.gov/data/gridded/tables/daily.html)
