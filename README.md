# weatherpy

The goal of this project is to prove that cities around the equator are hotter than cities near the poles.

In order to avoid bias in choosing cities around the world, I have generated random numbers for latitudes and longitudes and used CitiPy to find cities that match/closely resemble them. After collecting all the cities, I used Open Weather Map's API to retrieve data regarding these cities. 

After analyzing 500+ random cities around the world comparing the distance to the equator with temperature, humidity, cloudiness, and wind speed, I have concluded that the 

The cities that are closer to the equator tend to have a higher temperature compared to cities closer to the poles. However, the peak temperatures are from cities with latitutes around 20 degrees, which is a little bit above the equator and that can be explained by weather patterns experienced at the equator. 

By looking closely at the latitude vs humidity graph, one trend noticed is that there is no low humidity at the equator, all the data points are at 60-100% humidity. As you get closer to the poles, there are data points with low humidity (<50%). There are areas all around the world with 100% humidity, near or far from the equator. 

With the latitude vs wind speed graph, there seems to be no correlation between latitude and wind speed. The only trend that's noticed in this graph is that wind speed is usually below 15mph and the areas with high winds are all over the world. 