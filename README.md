# NYC CITI Bike


## Overview

Biking in New York City can be an adventerous, exciting and convenient way to see the city.  In a city that is dominated by cars and train-lines, CITI Bike has made bike sharing one of the most efficient, rewarding, and exhilarating ways to get around town.  Biking through the city allows riders to become familiar and comfortable with the city, all while exploring landmarks and culture as they ride along.  This creates a magical experience that is much different from simply taking public transit.  How can we replicate this magic in other cities, such as Des Moines, Iowa?  We will need to explore how biking sharing works in New York City, in order to scale the project for other cities.  Through analyzing CITI-Bike bike sharing data, we can answer many questions about the users, and when and where they like to bike. 


## Software / Languages

### Software
- Tableau Public
- Jupyter Notebook

### Languages
- Python


## Results

The user stories of different bike riding populations have been presented below, as well as on Tableau Public forum.  Please see the link below to access the full NYC CITI Bike Sharing dynamic and interactive dashboard.

[NYC CITI Bike Sharing via Tableau](https://public.tableau.com/app/profile/tobias.pratt/viz/NYCCitiBike_16601671394750/NYCCITIBiking)

### Checkout Times for Users

- By aggregating the total count of bikes and analyzing the duration each bike was used, we were able to determine:
  - The majority of bike users took rides for a duration between 3 and 10 minutes.
  - We are also able to determine the majority of users took rides that lasted a duration of less than 1 hour.
  - There were very few riders that took rides for over one hour.

![checkout times](Resources/checkouttimesbyusers.png)

### Checkout Times by Gender

- By aggregating the total count of bikes and analyzing the duration each bike was used by each gender, we were able to determine:
  - Male users accounted for the majority of bike users.
  - Although less female riders used the service, the female users had similar duration of bike rides as male users. 

![checkout times](Resources/checkouttimesbygender.png)

### Trips by Weekday per Hour

- By analyzing the amount of trips by weekday per hour, we were able to determine: 
  - Majority of riders took rides on Thursdays, with Mondays and Tuesdays also being prominent days for bike rides.
  - Most riders took rides between the hours of 8am and 9am, as well as 5pm and 7pm on most weekdays.
  
  - We saw the least amount of riders on Wednesdays and Sundays.
  - We saw the lease amount of riders between 10pm-6am.

![checkout times](Resources/tripsbyweekday.png)

### Trips by Gender (Weekday per Hour)

- By analyzing the amount of trips by weekday per hour per gender, we were able to determine:
  - Male riders accounted for the majority of riders between the hours of 8am and 9am, as well as 5pm-7pm.
  - Male riders account for the majority of riders on Thursdays.
  - Male and Female riders had equally active time periods for being active, with Thursday being the most popular day and 5-7pm being the most popular time for both user groups.

![checkout times](Resources/tripsbygender.png)


### User Trips by Gender by Weekday

- Male riders accounted for the majority of CITI Bike annual subscribers.
- There was not much difference in the number of male and female customers (non subscribers) on any day of the week.
- Male Riders that were annual subscribers were most likely to use the service on Monday, Tuesday, Thursday and Friday.
- Female riders that were annual subscribers were most likely to use the service Thursday, Monday and Tuesday. 

![checkout times](Resources/Usertripsbygender.png)

### Top Starting Locations

- Majority of Riders were found to start their trips in Manhantan below Central Park.
- Majority of Riders outside of Manhattan were found to start riders closer to the river.

![checkout times](Resources/topstartinglocations.png)

### Top Ending Locations

- Majority of Riders were found to end their rides in Mnahattan, also below Central Park.
- A larger number of riders however, were found to end their rides closer to Central Park, than those that started around Central Park.
- Overall, many rides began and ended toward the center of Manhattan.

![checkout times](Resources/topendinglocations.png)



## Summary

### Results Summary

- Overall, we found that CITI Bike users tend to be Male and appear to start their rides mostly around the center of the city.  
- Users were most active between 8am and 9am, as well as 5pm-7pm.
  - Considering these times in a busy, metropolitan city like New York, riders appear to be most active during commute times.  This is likely due to standard work schedules beginning around 9am and ending around 5pm.
  - Users are also most likely to live in the areas where they use the bikes, considering most bike rides lasted a duration of 30 minutes of less.
  - In addition, most bike rides began and ended in similar proximity.  This suggests that the many higher traffic stations around the city had similar activity for those beginning rides and those ending rides.
 
 ###  Additional Considerations
 
 - When reviewing this data, it may also be helpful to analyze data from different months of the year.  August is a summer month, with likely several tourists that may also use the service.  It would be interesting to analyze the stability of the business year round and when unpleasant weather is a factor.
 - It would also be helpful to determine the starting locations in comparison to the ending locations for a single ride.  We can use this to determine the how far average users travel and if male riders travel further than female riders, or if annual subscribers ride further than non-subscribers.
 - Lastly, it is important to analyze how often subscribers may use the service in times of unpleasant weather.  From this we can determine the best times of year to market to new potential annual subscribers.  

