# [DIVVY Top Station Analysis Dashboard](https://public.tableau.com/profile/sankalp4#!/vizhome/1_8_filters_16195161821810/TopStationsActivityDashboard)

## About Divvy

Divvy is Chicago's Bike Sharing System. With the city of Chicago Divvy publishes historical data about trips and makes it available for public use.

## About Dataset

The dataset used here is of Q1 and Q2 of 2019 shared in divvy's site [repo](https://www.divvybikes.com/system-data) .

The data is split into two tables.


```Station's Table``` consisting of

>* ```id```: ID attached to each station.
>* ```name```: station's Name
>* ```latitude```: station latitude
>* ```longitude```: station longitude
>* ```docks```: number of docks at the station


```Trip's Table```
>* ```trip id```: ID attached to each trip
>* ```bike id```: ID attached to each bike
>* ```trip duration```: time of trip in seconds
>* ```start time```: day and time trip started (CST)
>* ```end time```: day and time trip ended (CST)
>* ```from station id```: station id of the trip start
>* ```from station name```: station name of start
>* ```to station id```: station id of trip end
>* ```to station name```: station name of end
>* ```usertype```: Customer or Subscriber
>* ```birth year```: birth year of rider
>* ```gender```: gender of rider

2 ```Calculated Field``` has been made here.

```Seasons```: Spring, Summer , Winter( omitted others as data is of Q1 and Q2)
```Time Block```: Morning, Afternoon , Evening and Night.

An interactive dashboard has been made with filters ```usertype```, ```Time Block``` and ```Seasons``` showing no.of trips across user type, a geoviz station map with no. of trips per station, station ranking bar chart and Trip variation chart with time.

[Link to Project]((https://public.tableau.com/profile/sankalp4#!/vizhome/1_8_filters_16195161821810/TopStationsActivityDashboard))





