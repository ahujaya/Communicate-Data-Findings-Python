# Communicate-Data-Findings-for-BayWheels-Bike-Sharing-System-

# Bay Wheels Bike Sharing System Usage Pattern
## by Yash Ahuja


## Dataset

The dataset consists of approx. 180,000+ bike trips that happened in Feb 2019 covering the San Francisco Bay Area. The data can be downloaded from [here](https://s3.amazonaws.com/baywheels-data/index.html). The dataset contains features regarding trip duration, station information and annonymized member information (user type, gender etc). Visualizations are created from wrangled and cleaned data to facilitate exploration analysis and help discover usage pattern and rider characteristics.s

## Summary of Findings

In exploration, I found that approx. 95% of the trips have duration around 25 minutes implicating that on average, the bike trips are of short duration. Moreover, more than two thirds of the trips have customers or subscribers having age 25-40 years implicating that majority of the users are middle aged adults. A large number of trips are observed in mornings at 8AM & 9AM and evenings at 4PM, 5PM & 6PM implicating that majority of the trips are taken before and after the usual office hours. As majority of the trips were taken before and after the usual office hours, it is no surprise that majority of the trips have taken place at weekdays (Mon-Fri) as compared to weekends (Sat-Sun). Majority of the users are Subscribers and the difference between the number of Subscribers and Customers is substantial and the same can be said for male users over female users. Also, majority of the users have not used bike share for their entire trip.

There is no linear relationship between duration and age. However, they both varied daily/weekly and across different rider characteristics:

- On average, bike rides on weekends (Sat-Sun) have longer durations as compared to bike rides on other weekdays (Mon-Fri).
- On average, bikers on weekdays (Mon-Fri) are older than bikers on weekends (Sat-Sun).
- On average, users who are 'Customer' have longer bike trip durations as compared to users who are 'Subscriber'.
- On average, female bikers have longer bike trip durations as compared to male bikers.
- The average age of male bikers is higher than that of female bikers.
- The average age of 'Subscriber' and 'Customer' type bikers is approximately same. However, Subscriber user type has more older people compared to customer user type and the same goes for male users over female users.
- On average, bike rides that start between 8 AM to 6 PM have longer durations as compared to other times of the day.
- There is no significant difference between the age of the bikers starting between 5 AM to 6 PM.
- The average age of bikers who start at 4 AM is highest as compared to bikers who start at other time frames and interestingly it is even higher than the overall average age (34) of all the bikers. It may be because of very less number of bikers starting at this time period.
- On average, bikers starting between 12 midnight to 3 AM have lower age as compared to other time frames.
- On average, trip duration and age of bikers who did not use the bike share for their entire trip is higher as compared to those who used it for their entire trip.

Daily and Weekly Bike Trip Trends of different rider characteristics:

- Thursday, 8 AM and 5 PM has the highest bike trips across 7 days and 24 hours.
- Overall, weekdays have higher number of trips than weekends.
- Overall, Subscribers have higher number of trips than customers across all times of the day. Moreover, 8 AM and 5 PM has the most 'Subscriber' bikers compared to other hours. Also, 5 PM has the most 'Customer' bikers compared to other times of the day.
- Overall, Subscribers have higher number of trips than customers across all days of the week. Moreover, Thursday has the most 'Subscriber' and 'Customer' bikers compared to other days.
- Overall, male bikers have higher number of trips as compared to female and other gender type across all the times of the day (hour) and days of the week.
- Most of the Subscriber bikers are male. Most of the Customer bikers are also male.
- 8 AM and 5 PM has the highest male and female bikers across 24 hours
- Thursday has the most male bikers compared to other days. It also has the most female bikers compared to other days.
- Out of all the customer bikers, all of them have not used bike share for their entire trip whereas in case of subscribers, a very small proportion of them have used bike share for their entire trip.

Daily and Weekly Average Bike Trip Duration of different user and gender types:

- Customers have higher average bike trip duration than subscribers across all the times of the day (hour) and days of the week with customers having higher average bike trip duration on weekends (Sat-Sun) as compared to weekdays (Mon-Fri) and the same could not be said for subsribers as their difference between weekdays and weekends in terms of average bike trip durations is not significant.
- Female bikers have higher average bike trip duration than male bikers across all the days of the week with female bikers having higher average bike trip duration on weekends (Sat-Sun) as compared to weekdays (Mon-Fri) and same goes for male bikers.

Distinguishing usage patterns together for Customers and Subscribers:

The efficient/short period of usage for subscribers, involving more older people as compared to customer bikers, corresponds to their high concentration on rush hours Monday through Friday, indicating that they use the system heavily on weekdays, compared to customer bikers, primarily for work commute. Whereas, customer bikers who have more younger people as compared to the subscribers have more relaxing and flexible usage pattern. It is supported by the fact that they're taking advantage of the bike sharing system quite differently from the subscribers as they use the system heavily on weekends (especially in the afternoon) compared to subscribers for city tour or leisure purpose probably.
The above insight was further supported by the fact that when we used the findings from the univariate exploration that most of the bikers were in the age group 25-40 years and divided the users into two separate age groups middle aged adults (20-40) and adults (more than 40), it was found that Customer bikers bike longer than Subscriber bikers for both middle aged adults and adults. Additionally, 'Customer' bikers bike longer on weekends as compared to weekdays for both middle aged adults and adults implicating that they use the system heavily for leisure purposes whereas the difference between weekdays and weekends in terms of biking duration for both middle aged adults and adults is insignificant in case of Subscriber bikers as they use the system primarily for work commute. 

However, a very little distinguishing pattern of biking duration of was observed when we compared the biking duration of middle aged adults and adults for all days of the week across different times of the day as both middle aged adults and adults bike for longer periods in approx. same time frames on weekends (Sat-Sun) as compared to weekdays (Mon-Fri):

1. 10 AM - 5 PM on weekends for middle aged adults
2. 6 AM - 6 PM  on weekends for adults

Also, no distinguishing pattern of biking duration was observed among middle aged adults and adults for all days of the week across gender types which might be a result of very less female biker data as compared to male bikers.

## Key Insights for Presentation

For the presentation, I focused on the distribution of trip duration and age. Then, I introduced trip duration & age of riders across different days of the week followed by user and gender types. Afterwards, I introduced daily and weekly bike trip trends of different user and gender types followed by the daily and weekly average bike trip duration of the same rider characteristics. Finally, I introduced the distinguishing usage patterns for Customers and Subscribers and dove deeper into the insights provided by them by presenting the average bike trip duration of Customers and Subscribers for different age groups (middle aged adults and adults).

## Incorporating feedback
First, I used 'rocket_r' color palette for describing the distinguishing usage pattern for Customers and Subscribers and after getting feedback from my friend saying that he would have preferred a more differentiating palette, I changed the palette to 'inferno_r'.

