# python-api-challenge

In this challenge, we used OpenWeatherMap API, Geoapify API, citipy and hvPlot to generate data about random cities and create plots . 

In the first part, WeatherPy, we retrieved weather data from those cities using the OpenWeatherMap API. We then created DataFrames that contained information on the cities. After, we created scatter plots showing the relationships between latitude and different weather variables. Then, we plotted more scatter plots that show those weather relationships, but in relation to the northern and southern hemispheres. 

In the second part, VacationPy, we created a map using hvPlot with points for the cities created in the first part of the assignment. Next, we narrowed down our DataFrame to only include cities that meet our ideal weather criteria. After, we created a new DataFrame that copy the city, country, lng, lat, and humidity columns from the previous DataFrame. This new DataFrame was named hotel_df and we added a new column called "Hotel Name". Using Geoapify, we searched for the first hotel located within 10,000 meters of each city in our DataFrame based on certain parameters. Finally, we plotted a map showing points for those cities in our hotels DataFrame and with a hover message showing the hotel name and country.
