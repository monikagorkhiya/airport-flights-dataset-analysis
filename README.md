# airport-flights-dataset-analysis

## CSV Field Explanation 
```
Day0fMonth : shows the size of the day in a month which has a value from 1-31
DayofWeek : shows what day of the week it is
carrier : The column carrier indicates the airline, but it uses two-character carrier codes.  (The carrier code for Delta is "DL", for American is "AA", and for United is "UA". Using these carriers codes, we check whether carrier is one of those.)
OriginAirportID : shows the specific id of an arrival airport
DestAirportID : shows the specific id of the destination airport
DepDelay : shows the departure time from the time it should be
ArrDelay : shows the difference between the arrival time and the expected time
```
    
#### Question - 1) List out all flights details based on the Origin airport name  and  Destination Airport  name  ?  argument is origin_airport_name to destination_airport_name

#### Question - 2) List out airportname and flights deails based on given city name 
#### Question - 3) List out airportname and flights deails based on given state name 
#### Question - 4) Top 10 most deleay flights on perticular airport -  argument is airport name
#### Question - 5) Total Number of Delayed Flights over 15 minutes
#### Question - 6) Find the Airport with Most Flight Traffic
	eg. Airport|total Flights|
	     | ORD | 10000|
	     | ATL | 65 |
#### Question - 7) List out flights of perticular date  - argument is fromdate to todate
#### Question - 8) Overall flight count from Top 5 Airports
#### Question - 9) Determine the overall average number of delays per airport.
#### Question - 10) Display the three carriers with the lowest number of delayed flights.
#### Question - 11) List out the airports average airport of each country.
#### Question - 12) List out summer flights of perticular year - arguments is year
#### Question - 13) Display list of flights which have an arrival delay by one hour
#### Question - 14) Which carrier has the worst delays? 
