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
      
      2). Use the citypy module to list the nearest city to the latitudes and longitudes. 
      
      3). Use the OpenWeatherMap API to request the current wather data from each unique city in your list. 
      
      4). Parse the JSON data from the API request. 
      
      5). Collect the following data from the JSON file and add it to a DataFrame: [1]. City, country and date. [2]. Latitude and longtitude. [3]. Maximum temperature. [4]. Humidity. [5]. Cloudiness. [6]. Wind speed.
      
2. Exploratory Analysis with Visualization

      1). Create scatter plots of the weather data for the following comparisions: [1] Latitude v.s temperature. [2]. Latitude v.s humidity. [3]. Latitude v.s. Cloudiness. [4]. Latitude v.s. wind speed. 
      
      2). Determine the correlations for the following weather data: [1]. Latitude and temperature. [2]. Latitude and humidity. [3]. Latitude and cloudiness. [4]. Latitude and wind speed. 
      
      3). Create a series of heatmaps using the Google Maps and Places API that showcases the following: [1]. Latitude and temperature. [2]. Latitude and humidity. [3]. Latitude and cloudiness. [4]. Latitude and wind speed. 
    
3. Visualize Travel Data 

Create a heatmap with pop-up markers that can display information on specific cities based on a customer's travel perferences. Complete these steps:

      1). Filter the Pandas DataFrame based on user inputs for a minimum and maximum temperature.
      
      2). Create a heatmap for the new DataFrame.
      
      3). Find a hotel from the cities's coordinates using Google's Maps and Places API, and Search Nearby feature.
      
      4). Store the name of the first hotel in the DataFrame. 
      
      5). Add pop-up markers to the heatmap that display information about the city, currrent maximum temperature, and a hotel in the city. 
      
