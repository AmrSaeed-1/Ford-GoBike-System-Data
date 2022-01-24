# Ford GoBike System Data
## by (Amr saeed)


## Dataset

this project is divided into 2 main parts:

1- perform an exploratory data analysis at the  Ford GoBike System dataset using python then visualize data , this part begin by 
*cleaning the data  
*understand its structure  
*perform visualizations using relationship to multivariate.

2-begin the explanatory data analysis  using relationship taken by the previous part, 
sort and display it in a way that audience can understand and conclude an idea stands on visualizations and documentation for better clearance

the structure of data has 16 features and 183412 trip those are (duration_sec, start_time, end_time, start_station_id, start_station_name, start_station_latitude, start_station_longitude, end_station_id, end_station_name, end_station_latitude ,end_station_longitude, bike_id, user_type, member_birth_year, member_gender, bike_share_for_all_trip).

I had
1- drop null vlaues
2- scaling duration in seconds to duration in minutes
3- dropping [other] type of gender for simplecity
4- scaling [member_birth_year] feature to [member_age]

## Summary of Findings

> from previous plot we get that the male users are usimg more rides while comparing with female and other with long durations , other types of customers are taking long rides while they are older (50 - 60)
>The multivariate exploration confirmed the previous explorations and figures.
>The rides are mainly concentrated on rush hours Monday through Friday,
indicates that workers and collage students are the top clients,
>The longest rides are in weekends due to jamming.
the number of users for male is higher but percentage is higher for women in trip duration.
> the week days are the working and collage days
> the day hours are working start & end hours of work
> that workers and collage students are the top clients
> the top crowded station at rush hours varing from the the crowded station during the day
and
> I conclude that people avoid crowds at peak times unless the trip is a working or study trip

## Key Insights for Presentation

> the insight spots are the crowed stations to rush times relationship so where the major demand trips need to be supported by service provider
> the Age distribution shows users from 20:40 so if the service provider tends to provide supported service should be allowed with target group of age