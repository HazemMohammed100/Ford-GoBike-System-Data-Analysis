# Ford GoBike System Data
## by Hazem Mohammed


## Dataset

> The data is provided by The Ford GoBike System. There are 183,412 bike rides with 16 features describing each indiviual ride like:

- Duration(sec), Bike id, User type, Member birth year, Member gender, Bike share for all trip.
- Start time, Start station id, Start station name, Start station latitude, Start station longitude.
- End time, , End station id, End station name, End_station latitude, End station longitude.
- Most variables are categorical except for the ride duration 'duration_sec' and the start and end stations longtiude and latitude and the member birth year.
- 

## Summary of Findings

- The ride duration is mostly between 1 and 30 minutes, but there are bike rides that go longer than that. Plotted on a logarithmic scale, the distribution of bike ride duration takes on a right-skewed shape.
- There are 329 different stations. I displayed the top 10 start stations and top 10 end stations according to the count of bike rides.
- The bikes are mostly used during workdays (Monday to Friday in the USA), so it is viral transportation for people to get to work.
- The data is collected over the month of February of 2019.
- Bikes are mostly used during workdays (Monday to Friday in the USA), so it is viral transportation for people to get to work.
- The end time graphs are very similar to the start time graphs, so we can conclude that most rides start and end on the same day.
- Many people use the service as transportation to work since the count of bike rides is very high at 8 a.m. and 5 p.m. which translates to people going to work and returning back.
- Since most rides' duration are below 30 minutes, most rides will start and end at the same hour which is obvious from the graphs.
- There were 4618 different bikes, so I displayed the most used 50 bikes according to bike ride counts.
- The bikes that have ids ranging from 4200 to 5800 and over 6000 tend to be used more than other bikes. It could be related to certain stations.
- Nearly 90% of the users have a subscription. 
- Males are nearly 75% of the people using the service, but females are only 23.3%.
- Most users are born after 1960 and only a few are born before.
- So by the time the data was collected most users' ages ranged between 19 and 59.
- 90% of the members are not enrolled in the Bike Share for All program for low-income residents.
- Nearly all the rides started and ended on the same day except for 0.2% of the rides started and ended on different days.
- I think the number two-day rides that started on Friday and ended on Saturday is the highest because it is the start of the weekend.
- The difference between the count of subscriber and customer users is noticeably less in two-day rides than in one-day rides.
- The number of older people born before 1949 who are customers and don't have a subscription is very low, but it increases with younger people.
- Male users make many bike rides starting on Saturday and ending on Sunday compared to female users.
- The number of bike rides for all genders is almost consistent on work hours from 7 a.m. till 5 or 6 p.m.
- There are no customer users who are enrolled in the Bike Share for All program for low-income residents.
- Most users have a subscription and are not enrolled in Bike Share for All program for low-income residents
- There are a lot of bike rides between the stations with ids less than 100 and these stations use the bikes with ids ranging from 4500 to 5500, which explains the high usage rate of these bikes.
- As explained before that stations with ids less than 100 have more bike rides than other stations especially during work hours.
- Most bike rides durations are less than an hour and it is very clear by now that they are during work hours.
- The number of bike rides is the lowest on weekends and rises on workdays, but it is noticeable that during workdays they start the lowest on Mondays and increase slightly till they reach their maximum points on Thursdays.



## Key Insights for Presentation

- The ride duration is mostly between 1 and 30 minutes, but there are bike rides that go longer than that. Plotted on a logarithmic scale, the distribution of bike ride duration takes on a right-skewed shape.
- Many people use the service as transportation to work since the count of bike rides is very high at 8 a.m. and 5 p.m. which translates to people going to work and returning back.
- Most bike rides durations are less than an hour and it is very clear by now that they are during work hours.
- Most users are born after 1960 and only a few are born before.
- So by the time the data was collected most users' ages ranged between 19 and 59.
- 90% of the users are not enrolled in the Bike Share for All program for low-income residents.
- Nearly 98% of bike rides start and end at different stations.
