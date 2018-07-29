# Analysis-of-Mobile-Food-in-SF

## Summary
We chose to do this project because we are all foodies who are passionate to explore local authentic street food. We found the interesting datasets about mobile foods in San Francisco on data.sf.org. The important fields that we used are the columns about mobile food vendors and descriptions, the time of operations, and the locations. We mainly used Pandas and Numpy modules to do analysis, and Matplotlib and Seaborn to create visualizations about the mobile food in San Francisco in order to gain interesting insights.

## Key Visualizations
Below are three key visualizations that can give us an overall picture of the three important aspects about mobile foods in San Francisco: what, when and where. 

1. What are the most popular mobile food items that are offered by mobile food vendors in San Francisco?
![](Visualization%20Images/MobileFoodWordCloud.png)

As we can see from the above word cloud image of mobile food items in San Francisco, the most popular food items offered by the vendors include food items on cold truck, snacks, packaged sandwiches, pitas, hot drinks and breakfast. 


2. How many mobile foods are available during certain times and days of the week?
![](Visualization%20Images/MobileFoodHeatmap.png)

The above heatmap shows that much more mobile foods are available during week days than weekends. Also, the most mobile foods are available during lunch and brunch hours (9am-2pm). This shows that most mobile foods target to serve lunches and brunches for working professionals. 


3. Where in San Francisco are the mobile foods located?
![](Visualization%20Images/MobileFoodLocationsbyFacilityType.png)

From the initial view of the mobile food business locationson in San Francisco map for both trucks and push carts, we can see there are only few points on the west side. Most of the points are concentrated on the east and middle side, especially the northeast corner, and these areas are San Francisco's commercial areas with the most companies and business. This further shows that the mobile foods target to serve the working professionals. 

The food truck business locations are the orange dots on the map. Most food trucks are concentrated on the east and middle side, and only few food trucks are operating on the west side. The push carts business locations are the blue dots on the map, most push carts are located along Market Street, which is the main business street in San Francisco.
 

## Datasets
Below are the datasets that we found on data.sfgov.org :

Dataset 1: Mobile Food Schedule

Date Created: September 24, 2012
Date Updated: July 14, 2018
Intro:A child data set of --Mobile Food Facility Permit-- includes day of week, start / end time, location and a description of type of food sold by vendor. Mobile Food Facility Permit data is here: https://data.sfgov.org/d/rqzj-sfat

Dataset 2: Mobile Food Facility Permit

Date Created: September 24, 2012
Date Updated: July 14, 2018
Intro: Mobile Food Facility Permits including name of vendor, location, type of food sold and status of permit. Mobile Food Facility Permit Schedule is here https://data.sfgov.org/d/jjew-r69b

Dataset 3: Mobile Food Summary

Since all of the same attributes for the above two datasets are duplicate, we have to merge these two datasets by using vlookup in Excel.

## Python Jupyter Notebook in nbviewer
https://nbviewer.jupyter.org/github/andrewhuangca/Analysis-of-Mobile-Food-in-SF/blob/master/Jupyter%20Notebook/Mobile%20Food%20in%20SF_Data%20Visualization-Final-0728_v1.ipynb
