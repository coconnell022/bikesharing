# bikesharing

[link to tableau public dashboard](LINK GOES HERE)

## Overview of the Statistical Analysis

The purpose of this project is to create worksheets, dashboards, and stories from New York City bike-sharing data using Tableau to present a business proposal for a bike-sharing company. The dataset used is a Citi Bike CSV file of all bike-sharing data from the month of August in 2019 that contains information like user type, gender, birth year, and starting and stopping points/times. The data was analyzed to provide breakdowns and visualizations that demonstrate trends and successful results of Citi Bike in NYC. The objective is to provide a comprehensive bike trip analysis that will convince investors to partake a bike-sharing program in Des Moines. Below shows a breakdown of the gender and total number of rides from this data set.

<p align="center">
    <img src="https://github.com/coconnell022/bikesharing/blob/main/Viz/Number%20of%20Rides.png?raw=true" height = "250" width="350">
    <img src="https://github.com/coconnell022/bikesharing/blob/main/Viz/Gender%20Breakdown.png?raw=true" height = "250" width="350">
</p>


    Resources
        - Data Sources: 201908-citibike-tripdata.csv
        - Software: VS Code, Tableau, Python, Jupyter Notebook

## Results

### Duration of bike rides for all riders and genders

![alt text](https://github.com/coconnell022/bikesharing/blob/main/Viz/Checkout%20Times%20for%20Users.png?raw=true)

The visualization above shows bike checkout times for all users throughout the day in hours and minutes. It can be seen that the majority of users are taking the bikes out for about 3 to 6 hours during the month of August. It is likely that the majority of people who are taking the bikes out longer than 1 hour are tourists using bikes for a long portion of the day, compared to locals who are using bikes to commute. 

![alt text](https://github.com/coconnell022/bikesharing/blob/main/Viz/Checkout%20Times%20by%20Gender.png?raw=true)

The graph above demonstrates the checkout times for all user throughout the day based on gender. As shown in the graph, male riders are more likely to take the bike out for longer durations compared to women and unknown genders. It is also important to note that over 65% of bike riders during the month of August were male. 

### Number of trips taken by the hour for each day of the week, for all riders and genders

![alt text](https://github.com/coconnell022/bikesharing/blob/main/Viz/Trips%20by%20Weekday%20per%20Hour.png?raw=true)

As shown in visualization above, there is a breakdown of the number of rides based on the weekday and hour. The legend on the right shows that as the color darkens, there are more rides. It can be seen that most rides are taken between 6am to 8am and 5pm to 7pm during the week for commuting. Whereas on the weekend, the bikes are used consistently between the hours of 9am and 7pm. 

![alt text](https://github.com/coconnell022/bikesharing/blob/main/Viz/Trips%20by%20Gender%20(Weekday%20per%20Hour).png?raw=true)

The visualization above demonstrates a similar breakdown but adds an additional analysis by gender. Since the majority of riders during this month were male riders, the data reflects that female and unknown genders took less bike rides. 

### A breakdown of days of the week that users are more likely to ride by user type and gender

![alt text](https://github.com/coconnell022/bikesharing/blob/main/Viz/User%20Trips%20by%20Gender%20by%20Weekday.png?raw=true)

As shown in visualization above, an analysis of user type by gender and weekday is displayed. Overall, there are about 1.5 million more subscriber rides than customer rides during the month of August. Of the 2 user types and genders, male subscribers are more likely to use the bikes throughout the week. It is also important to note that the most common day for customers to use the bikes are on the weekend, indicating that they may be more likely tourists. Another important takeaway from this visualization is that for those who mark the unknown gender, they are more likely to be customers than subscribers, which indicates that they are possibly tourists who are using the bike just 1 or 2 times and do not wish to submit their personal information. 

### Top starting and stopping locations

![alt text](https://github.com/coconnell022/bikesharing/blob/main/Viz/Top%20Starting%20Locations.png?raw=true)

The map above is demonstrating a breakdown of the top starting locations throughout the city for all bike users. It can be seen by size and color that users are more likely to pick up a bike in midtown Manhattan compared to the other parts of NYC. Since the month of August is in summer it is likely that many users are tourists who are picking up bikes in heavily tourist filled areas in the city near attractions. 

![alt text](https://github.com/coconnell022/bikesharing/blob/main/Viz/Top%20Ending%20Locations.png?raw=true)

The map above that demonstrates top ending locations is very similar to the stop starting locations. One possible explanation for this is that most bike riders, whether they are locals or tourists, are probably picking up their bikes outside of their hotels or apartments and are ending their rides near their pick up spot. Therefore the top starting locations will almost always resemble the top ending locations for a bike-sharing company. 

## Summary

Overall, it would be a great idea to open and invest in a bike-sharing company in Des Moines. As shown in the analysis and visualizations provided, there were over 2.3 million Citi Bike rides taken by all types of people during August 2019. Of every type of user, the most common is a local male subscriber in his 20s to 40s who lives in one of the higher populated areas of the city. Of all rides, subscribers make up the majority compared to customers, therefore it is likely that people who live in the area will sign up for monthly subscriptions so that they can utilize the bike for daily commutes; whereas customers are more likely to be tourists using the bike for one time rides on their visit. A bike-sharing company will definitely be successful with the proper marketing strategies in a urban setting amongst tourists, locals, and people of all ages and genders. 

### Two additional reccomended visualizations

Two additional visualizations that can be done for future analysis using this data set are user trips by age and user trips by gender as shown below. Both can be used for a deeper analysis but indicate that the majority of users are adult male subscribers.

![alt text](https://github.com/coconnell022/bikesharing/blob/main/Viz/User%20Trip%20by%20Age.png?raw=true)
![alt text](https://github.com/coconnell022/bikesharing/blob/main/Viz/User%20Trips%20by%20Gender.png?raw=true)


        Caroline O'Connell
        January 17th, 2021

