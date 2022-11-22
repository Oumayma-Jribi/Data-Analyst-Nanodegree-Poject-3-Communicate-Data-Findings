# Ford GoBike System Data Exploration

## Dataset

This data set includes information about individual trips made in a bike-sharing system covering the greater San Francisco Bay area.
A a listing of Bike Share data portals can be found here, it should list the city, link to the data system and outline the data currently provided.
[here](https://github.com/BetaNYC/Bike-Share-Data-Best-Practices/wiki/Bike-Share-Data-Systems).


## Summary of Findings

In the exploration, I found out that: 

- Although members of gender type "Other" are a minority, it was shown that they have the longet trip duration with an average of approximately 1000 seconds.
When comparing only males and females, females seem to have a slightly higher average trip duration.
- When studying the relationship of trip duration with birth year, there seems to be a constant range of average trip duration
 except for 2 peaks for the years 1988 and 2000.
- Customers have longer trip durations than subscribers
- "The Embarcadero at Sansome St" corresponds to the starting station with the highest average trip duration, 
followed "San Franncisco Feryy Building" and "Powell St BART Station".
- Some hours during the day (16, 17, 18 o'clock and 7, 8, and 9 o'clock) were seen to have more frequent trips, 
this can be supported by the fact that these hours correspond to the evening and morning rush hours respectively. 
However there doesn't seem to be an effect of the hours of the day on the trip duration.
- When investigating the relationship between user gender and user type, it was shown that most of "Customers" are of gender type "Other"
- The graph depicting the relationship between gender and the enrollment in the bike share program showed that gender has no effect on enrollent.

- Younger females seem to have longer trip durations.
- Males have slightly higher trip durations than the average for those born between 1988 and 1992, as well as those born on 2000.
- For the gender type "Other", highest trip durations are for members born on 1989, 1999, followed by the years 1194, 1998, and 1993.
- For those enrolled in the bike share program, the highest trip duration corresponds to the starting station of "San Francisco Ferry Building" with a remarkably high average of 2958 seconds, 
followed by "Steuart St at Market St" and "The Embarcadero at Sansome St".

## Key Insights for Presentation

- The distribution of the variable of interest duration_sec
- Relationship between trip duration and member gender
- Relationship between trip duration and user type
- Relationship between trip duration, gender, and birth year
- Relationship between trip duration, bike-share program enrollment and starting stations (as it can give an insight about
where enrollers of this program are located and where they use the system most)