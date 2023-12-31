# Ford GoBike System Data
## by Riga

1. Data Exploration with Python: Utilized Python to delve into a dataset containing detailed records of individual rides from a bike-sharing system in the greater San Francisco Bay area in 2019.

2. Data Wrangling: Performed tasks to standardize the data format, cleanse any inconsistencies, and coded to calculate descriptive statistics.

3. Visualization with Matplotlib and Seaborn: Created histograms and bar charts using matplotlib and seaborn to represent the data. These visualizations aid analysts in understanding data distributions through both univariate and multivariate exploration.

4. Insights from Analysis: Through the visualizations, it was discerned that various factors, such as personal details (like gender, age, and user type) and station location, significantly influence the number of users. However, these factors display a minimal impact on the ride duration.

## Dataset

> The dataset is consists of 183412 rows and 16 columns. 
The column 'duration_sec' represents the time of each bike trip;
The column 'start_time' and 'end_time' indicate the data and time of each trip at starting and end points;
The column 'start_station_id', 'end_station_id', 'start_station_name','end__station_name' denote the station IDs and names at the starting and end station. Their geological information is provided by column 'start_station_latitude','start_station_longitude','end_station_latitude' and 'end_station_longitude';
The column 'bike_id' is the ID of the bike;
The personal information contains users' age, gender, user type can be gotten from columns 'member_birth_year', 'member_gender','user_type';
The last column 'bike_share_for_all_trip' shows if the shared bike has been used for the whole trip.


## Summary of Findings

> Based on the plot and analysis, the analyzed factors, including personal information (gender, age, and user type) and station location, have a significant impact on the number of users, but they show relatively little effect on ride duration.

1. Gender and user type have a substantial influence on the users' riding time. The analysis indicates distinct patterns in riding durations between different gender and user type categories, with notable variations in the duration distributions.

2. Age does not appear to be a determining factor in ride duration. The analysis does not show significant variations in ride durations based on different age groups, indicating that age might not strongly affect how long users ride.

3. Station location emerges as a crucial factor that affects users' riding duration. The analysis suggests that certain station locations experience varying riding durations, with some locations showing longer average ride times compared to others.

In conclusion, understanding the impact of different factors on the number of users and ride duration can provide valuable insights for optimizing the bike-sharing system and tailoring services to meet the diverse needs of users based on their personal information and station preferences.


## Key Insights for Presentation

> 1. Relation of duration time and number of users based on gender and user type: Gender and user type have a significant impact on the number of users but show relatively little influence on the ride duration, which remains concentrated within specific ranges. Male users dominate the chart, with a peak count of around 12,000 users and durations between 5 to 10 minutes. Female and other genders also show peaks in this duration range, but with lower user counts. Moreover, the bar plot reveals that subscribers form the majority of users, and both customer and subscriber groups have peak duration times within the 5 to 10-minute range.
2. Relation of duration time and number of users based on age distribution: The analysis reveals that age distribution significantly impacts the number of users but has relatively little effect on the ride duration, which remains concentrated within specific ranges. The heat map provides an insightful overview of the distribution concerning duration, number of users, and age demographics. The majority of users, exceeding 1000 individuals, fall within the age range of 22 to 70 years old, with their riding durations generally below 100 minutes. Notably, the largest user group comprises individuals aged between 30 and 40, with a substantial count exceeding 7000. Additionally, there exists a small group of users whose reported age exceeds 140 years old. In summary, age distribution has a significant influence on individual counts but exerts a lesser effect on ride duration.
3. Relation of duration time and number of users based on top 10 popular stations: The complex bar plot matrix, focusing on the top 10 popular stations, provides a comprehensive view of the distribution of the number of users against ride duration for both start and end stations. The y-axis exhibits substantial variations in individual counts across different stations, with peak values ranging from around 750 to over 2000 people.
Simultaneously, the x-axis representing the duration time predominantly concentrates within the 0 to 30-minute range. This visualization demonstrates that station location has a significant impact on the number of users but has relatively little effect on the ride duration, as the majority of durations are confined within a specific time frame regardless of the station location.
