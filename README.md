# Weather v Latitude
When Weather_Py is run, weather data is collected and output to a csv file. The data is also charted by latitude vs. cloudiness, humidity, wind speed, and temperature.

## Requirements
- pandas
- numpy
- matplotlib
- requests
- citipy

## Observable trends
1) Based on the maximum temperature graph generated, the temperature does in fact seem to increase as latitude approaches 0, the equator.
2) Based on the cloudiness chart, there seem to be clusters of cloudiness levels. From -35 to -20 degrees and again from 10 to 60 degrees there tend to be more cloudiness percentages of zero. There are two clusters at 75% cloudiness around -10 to 10 degrees and again around 50 to 65 degrees. This indicates an almost sinusoidal relationship, potentially mimicing the wavy nature of the jetstream, though this could also be a purely coincidental observation based on that days' measurements.
3) Based on the wind speed graph, there seem to be higher wind speeds approaching the poles and more consistently lower wind speed closer to the equator.