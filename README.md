# Traffic-volume-prediction
The goal of this project is to figure out what the traffic on a given road will be, from the weather data, date, time of the day, and if the day is a holiday.

The dataset has 8 features:

holiday: a categorical variable that indicates whether the date is a US national holiday or a regional holiday (such as the Minnesota State Fair).

temp: a numeric variable that shows the average temperature in kelvin.

rain_1h: a numeric variable that shows the amount of rain in mm that occurred in the hour.

snow_1h: a numeric variable that shows the amount of snow in mm that occurred in the hour.

clouds_all: a numeric variable that shows the percentage of cloud cover.

weather_main: a categorical variable that gives a short textual description of the current weather (such as Clear, Clouds, Rain, etc.).

weather_description: a categorical variable that gives a longer textual description of the current weather (such as light rain, overcast clouds, etc.).

date_time: a DateTime variable that shows the hour of the data collected in local CST time.

traffic_volume: a numeric variable that shows the hourly I-94 reported westbound traffic volume.

RANDOMFORESTCLASSIFIER was used for making the predictions.


