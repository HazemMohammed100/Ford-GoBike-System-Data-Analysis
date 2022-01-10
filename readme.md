# Ford GoBike System Data
## by Hazem Mohammed


## Dataset

> The data is provided by The Ford GoBike System. There are 183,412 bike rides with 16 features describing each indiviual ride like:

- Duration(sec), Bike id, User type, Member birth year, Member gender, Bike share for all trip.
- Start time, Start station id, Start station name, Start station latitude, Start station longitude.
- End time, , End station id, End station name, End_station latitude, End station longitude.
- Most variables are categorical except for the ride duration 'duration_sec' and the start and end stations longtiude and latitude and the member birth year.


## Summary of Findings

- The ride duration are mostly between 1 and 30 minutes, but there are bike rides that go longer than that. Plotted on a logarithmic scale, the distribution of bike ride duration takes on a right skewed shape.
- There are 329 different stations. I displayed the top 10 start stations and top 10 end stations according to count of bike rides.
- The bikes are mostly used during workdays (Monday to Friday in USA), so it is a viral transportation for people to get to work.
- The data is collected over the month of February of 2019.
- Bikes are mostly used during workdays (Monday to Friday in USA), so it is a viral transportation for people to get to work.
- The end time graphs are very similar to the start time graphs, so we can conclude that most rides start and end at the same day.
- Many people use the service as a transportation to work, since the count of bike rides is very high at 8 a.m. and 5 p.m. which translates to people going to work and and returning back.
- Since most rides duration are below 30 minutes, so most rides will start and end at the same hour which is obvious from the graphs.
- There 4618 different bikes, so I displayed the most used 50 bikes according to bike ride counts.
- The bikes that have ids ranging from 4200 to 5800 and over 6000 tend to be used more than other bikes. It could be related to certain stations.
- Nearly 90% of the users have a subscribtion. 
- Males are nearly 75% of the people using the service, but females are only 23.3%.
- Most users are born after 1960 and only few are born before.
- So by the time the data was collected most user's ages ranged between 19 and 59.
- 90% of the members are not enrolled in the Bike Share for All program for low-income residents.
- Nearly all the rides started and ended on the same day except for 0.2% of the rides started and ended on different days.
- I think the of number two day rides that started on Friday and ended on Saturday is the highest beacuase it is the the start of weekend.
- The difference between count of subscriber and customer users is noticeably less in two day rides than in one day rides.
- The number of older people born before 1949 who are customers and don't have a subscribtion is very low ,but it increases with younger people.
- Male users make many bike rides starting on Saturday and ending on Sunday compared to female users.
- The number of bike rides for all genders is almost consistent on work hours from 7 a.m. till 5 or 6 p.m.
- There are no customer users who are enrolled in the Bike Share for All program for low-income residents.
- Most users have a subscribtion and are not enrolled in Bike Share for All program for low-income residents
- There are a lot of bike rides between the stations with ids less than 100 and these stations use the bikes with ids ranging from 4500 to 5500, which explains the high usage rate of these bikes.
- As explained before that stations with ids less than 100 have more bike rides than other stations especially at work hours.
- Most bike rides durations are less than an hour and it is very clear by now that they are during work hours.
- The number of bike rides is the lowest in weekends and rises up in work days ,but it is noticeable that during work days they start the lowest at Mondays and increase slightly till they reach their maximum points at Thursdays.



## Key Insights for Presentation

> Select one or two main threads from your exploration to polish up for your presentation. Note any changes in design from your exploration step here.
- The ride duration are mostly between 1 and 30 minutes, but there are bike rides that go longer than that. Plotted on a logarithmic scale, the distribution of bike ride duration takes on a right skewed shape.
- Many people use the service as a transportation to work, since the count of bike rides is very high at 8 a.m. and 5 p.m. which translates to people going to work and and returning back.
- Most bike rides durations are less than an hour and it is very clear by now that they are during work hours.
- Most users are born after 1960 and only few are born before.
- So by the time the data was collected most user's ages ranged between 19 and 59.
- 90% of the users are not enrolled in the Bike Share for All program for low-income residents.
- Nearly 98% of bike rides start and end at different stations.
