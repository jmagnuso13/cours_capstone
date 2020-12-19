## IBM Data Science Capstone

This project will attempt to assist an investor attempting to take advantage of this renewed interest in outdoor experience, by identifying smaller rural cities and towns with an abundance of outdoor activity and stable housing values to investigate an investment in a vacation rental home to list on the prominent rental platforms (Airbnb/VRBO/etc).

My datasets will leverage the [Foursquare Places API](https://developer.foursquare.com/docs/places-api/) to identify outdoor places and the [Zillow Home Values Forecast (City Admin Level)](https://www.zillow.com/research/data/) to identify home value trends in these areas.  

I will then cluster the data using K-Means Clustering to identify ideal markets for a potential investment into a vacation rental home.  The goal is to identify clusters of potentially undervalued markets from a housing investment perspective to identify cities with future growth potential for a housing investment.  


### Data Source Examples
#### Zillow Home Values Index
Zillow Home Value Index (ZHVI): A smoothed, seasonally adjusted measure of the typical home value and market changes across a given region and housing type. It reflects the typical value for homes in the 35th to 65th percentile range

#### Foursquare Places API
The Foursquare Places API will be used to identify Outdoor opportunities leveraging the 'Outdoors & Recreation' Category ID.  The output below shows some samples of how the foursquare app could be utilized.
``json
'meta': {'code': 200, 'requestId': '5fd44a674fe037099c612345'},
 'response': {'venues': [{'id': '51e30b94498e535deccfdea5',
    'name': 'Mt. Sneffels Trail Head',
    'location': {'lat': 38.02182290933693,
     'lng': -107.6715202730119,
     'labeledLatLngs': [{'label': 'display',
       'lat': 38.02182290933693,
       'lng': -107.6715202730119}],
     'distance': 267,
     'cc': 'US',
     'state': 'Colorado',
     'country': 'United States',
     'formattedAddress': ['Colorado', 'United States']},
    'categories': [{'id': '4bf58dd8d48988d159941735',
      'name': 'Trail',
      'pluralName': 'Trails',
      'shortName': 'Trail',
      'icon': {'prefix': 'https://ss3.4sqi.net/img/categories_v2/parks_outdoors/hikingtrail_',
       'suffix': '.png'},
      'primary': True}],
    'referralId': 'v-1607748199',
    'hasPerk': False},
   {'id': '55ef161d49
   ``

### Libraries Required
Numpy
Pandas
Matplotlib
SKlearn
Folium
Geopy

#### Zillow csv file stored in csv folder.  magnuson_capstone.ipynb contains code to run
