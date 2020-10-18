# World_Weather_Analysis

related questions: How might we provide real_time suggestions for our client's ideal hotels? 
(1). Within a given range of latitude and longitude and that 
(2). Provided the right kind of weather for the client.

## Basic Project Plan 
1. Task: Collect and analyze weather data across cities Worldwide.

2. Purpose: PlanMyTrip will use the data to recommand ideal hotels based on clients' weather preferences.

3. Method: Create a Pandas DataFrame with 500 or more of the world's unique cities and their weather data in real time. This process will entail collecting, analyzing and visualizing the data. 

## The analysis of the data will be split into three main parts, or stages.

1. Collect the data 

      1). use the Numpy module to generate more than 1,500 random latitudes and longtitudes. 
      
      2). Use the citypy module to list the nearest city to the latitudes and longittudes. 
      
      3). Use the OpenWeatherMap API to request the current wather data from each unique city in your list. 
