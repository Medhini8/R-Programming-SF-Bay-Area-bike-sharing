### R-Programming-SF-Bay-Area-bike-sharing
This Repository contains Exploratory Data Analysis of SF Bay area Bike Sharing using R

### Executive Summary
Congested streets and slow-crawling traffic are a fact of life in many metropolitan areas.Bike sharing is an innovative solution for such problems, and it works by dispersing a large fleet of publicly-available bikes throughout crowded cities for personal transport. In this paper, We will be analyzing San Fransico Bay area bike share data set to perform exploratory data analysis to reveal some insights about the bike rental usage in San Fransisco and then create an appropriate prediction model which help to expalin demand for bike rentals which inturn allows for the better allocation of resources.

### In this analysis we would like to explore the the factors of bike rental usage as given below:
Exploratory data analysis:
1.Are there more riders on the weekdays or weekends?
2.Are there more customers or subscribers using the service?
3.Which are the stations that tend to be the most ‘active’?

### Problem Statement
1. To analyze the impact of weather factors on bike rentals in order to efficiently manage bike
demand and supply.
2. Urban bikeshare systems are a wonderful way to get around a city. They are a great transit
option for tourists and commuters alike. However, it can be frustrating to find a totally empty
bikeshare station right at the start of a trip.
3.Better management of the maintenance schedule of bikes.

![image](https://user-images.githubusercontent.com/96325556/146664023-ed0c46e5-9d40-418c-a8b9-fb3fa5acb3cc.png)

![image](https://user-images.githubusercontent.com/96325556/146664064-dc50ecf7-9695-4a28-93d4-3db19fbe8d70.png)
![image](https://user-images.githubusercontent.com/96325556/146664077-662abd14-0a02-4c4d-bc69-bf42ae68b4e8.png)

Analysis:
A. 97% of trips are less than one Hour
B. Majority of the trips are less than 20mins
C. 99% of the trips are less than one day, so we can remove other trips as outliers.
D.Customers have higher average trip duration which verifies that customers are tourists who
uses bikes for a longer duration of time

### Exploratory Data Analysis
![image](https://user-images.githubusercontent.com/96325556/146664151-bd1cf984-f217-44eb-973c-51a5bf817ec6.png)
![image](https://user-images.githubusercontent.com/96325556/146664175-523b160d-8cc8-4d5a-a15f-ccf8b1fb76e8.png)
![image](https://user-images.githubusercontent.com/96325556/146664199-a20a824a-2b13-4eed-b6f6-376df842658a.png)

Observation from Plot1
* We can see that Customers have relatively stable trips made during weekdays and weekends.
Whereas biketrips by subscribers are more on weekdays than weekends.
Observation from Plot2
1.Average duration of trips by customers are higher than subscribers.
2. Both customers as well as subscribers have average trip duration higher during weekends.
3. Average trip time during day for subscribers is 8-9 mins and is almost same throughout the
day.

![image](https://user-images.githubusercontent.com/96325556/146664211-aed85798-fbc5-4f03-9f81-0c1be0016d12.png)
![image](https://user-images.githubusercontent.com/96325556/146664218-efa9b3db-ae37-459b-8fb5-351e52521355.png)

![image](https://user-images.githubusercontent.com/96325556/146664226-5928514a-7c3d-496b-b7ce-760d20de036f.png)

From these plots it looks like that pattern from before holds. That is, the total number of
trips peak around rush hour. Also notice the consistent small peak around lunch hour each
day at noon. We can also observe that the number of trips in winter slightly decreases.

Business Insights:
Since the number rides fall during winter, bike maintainance can be scheduled.

![image](https://user-images.githubusercontent.com/96325556/146664252-2823efce-9db8-42d9-bb53-bccb1f34e8e2.png)

We have bike sharing business in five cities in San Francisco bay area, namely San Francisco,
San Jose, Redwood city, Palo Alto and mountain view. Analysis of trips across cities reveal
that San Francisco has the highest number of trips per day, followed by San Jose. We again
ascertain the weekday- weekend pattern here, where number of trips in weekdays dominate
weekends in San Francisco.The number of rides occurred mainly during weekdays and fell to
a lower number during weekends. Hence, we would expect the availability of bikes problem to
occur more during weekdays.

![image](https://user-images.githubusercontent.com/96325556/146664264-cf4cef6b-481d-4597-97a8-d5fdc2a2a658.png)

We further wanted to clarify why San Francisco has more bike trips than other cities. One of
the reasons can be because San Francisco has highest number of stations, 35 station out of 74
station and also San Fransisco has more number of docks. Also, San Francisco is a popular
tourist place.

![image](https://user-images.githubusercontent.com/96325556/146664280-ae2161e9-b3d9-4147-a88f-f8fc3ae6e14b.png)

Customer trips involve “Embarcadero at Sansome” and “Harry Bridges Plaza (Ferry Building)” far more than Subscriber trips. Additionally, Subscriber trips involve “San Francisco Caltrain (Townsend at 4th)” and “San Francisco Caltrain 2 (330 Townsend)” far more than Customer trips.If everyone is travelling to, for example, San Francisco Caltrain (Townsend at 4th), then we will be expecting that station to be full quickly! Customer trips are centered more around tourist or visitor centers. For example, “Embarcadero at Sansome” is in close proximity to AT&T park, Little Italy and the North Beach Area. These represent hotspots for one-off transactions of the bike share program. Meanwhile the Caltrain-related stations represent gateways for people trying to enter the San Francisco
network for work.

Business Insights:
* Subscribers are monthly pass holders whereas customers are daily ticket takers. Also we
know that number of customers are significantly less as compared to the number of subscribers.
To attract more customers they should offer them some kind of attractive deals and discounts.

![image](https://user-images.githubusercontent.com/96325556/146664304-1b01692c-c812-40ae-9b07-d243778ea05e.png)

![image](https://user-images.githubusercontent.com/96325556/146664308-72204727-bad7-4e6d-8e05-c7137f03d78c.png)

The manager can look at the occupancy rate at peak hours and can analyze if bikes need to be transferred from high occupancy(meaning more bikes are available as proportion to docks) to low occupancy so that a case doesnot happens that a customer comes and bikes are not available. This will also lead to better allocation of resources.








