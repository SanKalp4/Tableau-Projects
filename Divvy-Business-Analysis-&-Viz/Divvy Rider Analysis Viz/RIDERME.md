[Divvy Rider and Business Analysis Story](https://public.tableau.com/profile/sankalp4#!/vizhome/DivvyRiderandBusinessAnalysisViz/Whoaretheriders)

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

### The Story
![Divvy Rider Business Analysis](https://user-images.githubusercontent.com/75038775/116785676-7515cf00-aab8-11eb-8c8f-9b9ac636691b.jpg)

* A interactive KPI story to understand the rider activity has been done to see the variation of tripduration , trip count in a day across the week with different user type. 

* This will help the company understand the different peak activity time and optimise the stock of bikes at the docks to avoid congestion and dissatisfaction amongst customers.

* Also at off peak times and week days , the company can analyse the data and run promotional activities to increase traffic at non peak times.

* Divvy has also introduced e-bikes in its ride portfolio , analysing the data through visualisation can help them optimise charging time to avoid charge depletion.

* If the docking stations have e-billboards, it can run 3rd party advertising to generate revenues at peak hours and charge a premium from advertisers.

[Link to Project](https://public.tableau.com/profile/sankalp4#!/vizhome/DivvyRiderandBusinessAnalysisViz/Whoaretheriders)
