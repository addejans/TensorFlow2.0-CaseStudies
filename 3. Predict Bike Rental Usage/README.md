You own an bike rental business and you would like to predict usage.

Data Reference:
   - Hadi Fanaee-T
   - Laboratory of Artificial Intelligence and Decision Support (LIAAD), University of Porto INESC Porto, Campus da FEUP Rua Dr. Roberto Frias, 378 4200 - 465 Porto, Portugal
   - [link](https://archive.ics.uci.edu/ml/datasets/bike%2Bsharing%2Bdataset)

Data Description:
 - instant: record index
 - dteday : date
 - season : season (1:springer, 2:summer, 3:fall, 4:winter)
 - yr : year (0: 2011, 1:2012)
 - mnth : month ( 1 to 12)
 - hr : hour (0 to 23)
 - holiday : wether day is holiday or not (extracted from http://dchr.dc.gov/page/holiday-schedule)
 - weekday : day of the week
 - workingday : if day is neither weekend nor holiday is 1, otherwise is 0.
 - weathersit :
   - 1 : Clear, Few clouds, Partly cloudy
   - 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
   - 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
   - 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
 - temp : Normalized temperature in Celsius. The values are divided to 41 (max)
 - hum: Normalized humidity. The values are divided to 100 (max)
 - windspeed: Normalized wind speed. The values are divided to 67 (max)
 - casual: count of casual users
 - registered: count of registered users
 - cnt: count of total rental bikes including both casual and registered


This is a regression task.
