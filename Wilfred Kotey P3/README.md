# Ford GoBike System Data Exploration


## by (Wilfred Kotey)



## Dataset

The dataset contains 174952 rows and 21 columns of information for the Ford GoBike System in a bike-sharing system including types of clients, their ages and gender and the number of trips taken and the duration. The dataset can be found in the udacity classroom https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv. 


## Summary of Findings

In the exploration, I found that males took the most trips out of all the genders on different weekdays. Also, they were the most abundant subscribers and casual users. This could be due to the fact that they were the most abundant gender in the dataset. I also found that people between the ages of 28 and 33 took the most trips and that as age increased the number of trips decreased. Also subscribers took more trips than the casual users and this can explain why the most trips were taken in the morning between 8 and 9am and in the evening between 5 and 6pm. These could be as subscribers were going to the work in the morning and returning in the evening.

## Key Insights for Presentation

For the presentation, I show the hours of the day when the most trips are taken and how this is influenced by the particular clientele. This is done by showing a clustered bar chart of the hours in the day and trips taken at each by casual customers and subscribers. Also, a heatmap is shown to display the counts of different clientele on each day of the week.

Also, I aim to show the relationship between age and length of the trip. This is done using a heatmap of the age and trip duration.

Finally, I show the trip duration of the genders using a seaborn pointplot with different colours to identify the different genders. This gives an indication of the genders and the duration of their trips.