# Technex----Analiticity---Pre-Event

ANALITICITY
OVERVIEW
This dataset contain the details about different factors affecting a tourist visit to a
National Park XYZ each day from 2011 to 2012. The Goal is to predict the total number
of visitors (both locals and foreigners) to the National Park.
The training data & test data is attached with the Problem Statement. Use the training
data to develop and train your model. The Goal attribute (i.e. the no of visitors) is given
in the train data but not in the test data.
You need to predict the number of shares attribute for the test data. The cost function
will be calculated as –
Cost Function = Square Root of {Summation of [(Square of predicted no. of visitors) -
(Actual no. of visitors)] }
Try to minimize the value of Cost Function as small as possible...ATTRIBUTE INFORMATION
There are in total 16 attributes:
1. Serial no.
2. date - date in “mm/dd/yyyy” format
3. time of year- 4 quarter of years ; namely 1 = spring, 2 = summer, 3 = fall, 4 =
winter
4. year – 2011-‘0’, 2012-‘1’
5. hour : hour (0 to 23)
6. day off - whether the day is considered a holiday
7. Weekday – day of the week
8. working day - whether the day is neither a weekend nor holiday
9. weather -
1 = Clear, Few clouds, Partly cloudy
2= Mist + Cloudy, Mist + Few clouds, Mist
3 = Light Snow, Light Rain + Thunderstorm + Scattered clouds
4 = Heavy Rain + Ice Pallets + Thunderstorm, Snow + Fog
10. temp - temperature in Celsius
11. feel temp - “feels like” temperature in Celsius
12. humidity - relative humidity
13. fog density- extent of fog, hinders visibility (normalised data)
14. foreigners – no of foreigners tourists
15. local - no of native tourists
16. total visitors – sum total of foreigners and local touristsGENERAL GUIDELINES
 For the first round of Analiticity ,team has to submit:-
1. Output (in .csv format)
Csv file containing the final result(total no of visitors) in sequential order, as of
test data.
2. Abstract (in pdf format)
