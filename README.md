# Coursera_Capstone
Coursera capstone project for Data science certificate

**1.1	Background** /n
A dataset was posted on Kaggle with the following description:
‘Since 2008, guests and hosts have used Airbnb to expand on traveling possibilities and present more unique, personalized way of experiencing the world. This dataset describes the listing activity and metrics in NYC, NY for 2019. This data file includes all needed information to find out more about hosts, geographical availability, necessary metrics to make predictions and draw conclusions.’

Alongside this description was a dataset from Airbnb. One of the questions asked was:  are we able to predict the prices of the listings based on the dataset provided. 

**1.2	Solution**
To solve this problem a regression model will be created to try to predict the prices of the Airbnb listings in the dataset. As the dataset contains information about geographical location and we are able to supplement the dataset with data from Foursquare. We hypothesise that adding information about the nearby venues will give a better prediction compared to the original dataset.

**1.3 Interest**
The parties that may be interested in the results are the original poster of the dataset as well as Airbnb.


**2. Data sources**
Data about AirBnB locations and prices were found in a Kaggle dataset from here.  The dataset contains information on the owner of the listing, name of the listing, the neighbourhood group, the neighbourhood, latitude and longitude, room type, availability, review metrics, minimum amount of nights, and price.

To complement this dataset Foursquare API was used to collect data on the venues surrounding the respective Airbnbs. The latitude and longitude of the Airbnbs was used to derive the nearby venues in a radius of 500 meter of the listing.


**NOTE:** The folium maps are not visible in the notebook but at this time i am unable to fix this. The code however does work when you execute it.
