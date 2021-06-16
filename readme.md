# (Ford Go bike Trip Data Exploration and Visualization)
## by (Phillip Ayebare)


## Dataset

> This document explores a dataset containing trip data for Ford Gobike with 183413 rows and 16 columns. In early July 2018, Lyft annouced the acquisition of Motivate (with USD 250 million), that operates bikeshare systems across New York(Citi Bike), Chicago(Divvy), D.C(Captical Bikeshare), Boston(BlueBikes) and San Francisco Bay area (**Ford GoBike**). 

- In the first part, an exploratory data analysis on a dataset Ford GoBike System Data is conducted. Python data visualization libraries are employed to explore the dataset’s variables and understand the data’s structure, oddities, patterns and relationships. The analysis in this part should be structured, going from simple univariate relationships to multivariate relationships.
- In the second part, The main findings from my exploration shall be conveyed through an explanatory analysis. A slide deck shall be created that portrays polished, explanatory visualizations to communicate my results.
- There are 183,412 data trips for fordgobike in the dataset with 16 features which include: duration_sec, start_time, end_time, start_station_id, start_station_name, start_station_latitude, start_station_longitude, end_station_id, end_station_name, end_station_latitude ,end_station_longitude, bike_id, user_type, member_birth_year, member_gender and bike_share_for_all_trip.


## Summary of Findings

> 20-40 year old male subscribers (average age of 35) riding an average of 1.7km on Thurday and Friday and averaging 10-12 minutes per ride (longer than other days) are the most common riders. The multivariate plots reinforced some of the patterns discovered in the bivariate and univariate exploration, the relationship between the multiple variables plotted are visualized altogether and information are presented combined. 

> 99% of bike rides had a duration of less than 53 minutes and fell within the range of 5 - 15 minutes in a normal distribution. Men riders outweigh female riders. Over 75% of bike rides are by males. It's not surprising that the most active hours are 8-9am and 17-18 hrs which are also peak hours for origin and destination trips. There ars more rides on Tuesday, Wednesday and Thursday (midweek) probably because people mainly leave their homes for different errands around the city. We can only find trends for day of the week becasue all the data is collected in 2019 in the month of February. Most riders are between the ages of 25-40 years

> Also, Average trip duration for subscribers are 10minutes, which is about two-third of customers'.



## Key Insights for Presentation

> Select one or two main threads from your exploration to polish up for your presentation. Note any changes in design from your exploration step here.

> The efficient/short period of usage for subscribers corresponds to their high concentration on rush hours Monday through Friday, indicating Subscribers' rides take place around commute time, on the contrary customers' rides take place the most during weekend, which represents the main purpose for the user type is different. The former is for convenience around commute time and the latter is more likely for leisure.