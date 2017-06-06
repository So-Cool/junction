# JUNCTION: Bristol Journey Times analysis #
This repository contains code and links to data that was used to analyse traffic patterns in Bristol.

## Datasets ##
* Car accident data available [here](https://data.gov.uk/dataset/road-accidents-safety-data). Data from 2014 and 2015 are used in this analysis.
* Bristol Journey Times data available [here](https://opendata.bristol.gov.uk/Mobility/Historic-journey-times/jdq4-bmr7). A snapshot of data up until 07/04/2017 14:47 UTC was used.
    - The speed and time are measured based on the number of cars passing between two traffic monitoring cameras (no car quantity given)
    - The coordinates of each monitoring point are latitude and longitude of the middle point between the two monitoring cameras (this can be the same for two routes in opposite directions)
    - Data between August 2015 and January 2016 were disregarded (January 2016 onwards are the most trustworthy)
    - The travel time is in seconds
    - The timestamp marks the start of the journey
    - The speed is in mph (converted to meters per second in this analysis)
* Simple weather data (rain measurements in particular) available [here](http://www.holiday-weather.com/bristol/averages/).

## Addressed Questions ##
- How do weather patterns influence the traffic load?
- Is there seasonal variation in the journey times?
- Is traffic bad at specific locations at specific times of the day?
- How do large city events / festivals affect congestion?

## ToDo ##
- [ ] If car journey times are bad, how does this affect alternative modes of transport?
- [ ] Can congestion data link with sentiment mapping?
