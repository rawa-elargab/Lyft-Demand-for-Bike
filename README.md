# Lyft-Demand-for-Bike

Description: Lyft, Inc. is a transportation network company based in San Francisco, California and operating in 640 cities in the United States and 9 cities in Canada. It develops, markets, and operates the Lyft mobile app, offering car rides, scooters, and a bicycle-sharing system. It is the second largest rideshare company in the world, second to only Uber. Lyft’s bike-sharing service is also among the largest in the USA. Being able to anticipate demand is extremely important for planning of bicycles, stations, and the personnel required to maintain these. This demand is sensitive to a lot of factors like season, humidity, rain, weekdays, holidays, and more. To enable this planning, Lyft needs to rightly predict the demand according to these factors

Data Description: The variables present in the dataset are:

instant: Serial number
dteday: date and day
hour: hour of the day (0 to 23)
season: season (1:spring, 2:summer, 3:fall, 4:winter)
yr: year (0: 2011, 1: 2012)
mnth: month (1 to 12)
hr: hour (0 to 23)
holiday: whether the day is a holiday or not
weekday: day of the week, Monday=0, Sunday=6.
workingday: if the day is neither weekend nor a holiday is 1, otherwise is 0
weathersit: four categories (1 to 4) ranging from best to worst weather
temp: normalized temperature in Celsius; the values are divided to 41 (max)
atemp: normalized temperature felt in Celsius; the values are divided to 50(max)
hum: normalized humidity; the values are divided to 100 (max)
windspeed: normalized wind speed; the values are divided to 67 (max)
casual: count of casual users
registered: count of registered users
cnt: The demand of bikes
