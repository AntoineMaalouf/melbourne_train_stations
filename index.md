## Discovering Possible Opportunities Around Melbourne Train Stations

### 1. Introduction
Train stations can create business opportunities by leveraging the increased foot and road traffic that is created around train stations. By Analyzing different attributes of each train stations within the Melbourne metropolitan area, it’s possible to locate underserved stations and evaluate the possibility of developing new businesses in its vicinity. 

Melbourne is a fast-growing city with high levels of adoption of public transport among its residents. It’s estimated that a total of 565 million trips are taken every year using at least one form of public transportation with 240.9 million that includes at least one leg by train [1]. 

Rents around popular stations such as Melbourne Central and Southern Cross stations have increased exponentially while competition have increased. It’s possible to discover new underserved stations that can give a competitive advantage to property developers and certain businesses by filling the needs in underserved areas without paying the higher rents charged close to the CBD.

### 2.	Data
Several Data sources will be used to analyze the current situation of train stations along the lines serving the Melbourne CBD along with established businesses around them
* Train Station Geolocations 
    * Provider: Department of Transport, Victoria, Australia
    * Format: Geojson file
    * License: Creative Commons Attribution (CC BY 4.0)
    * Usage: This dataset is used to determine the geographical coordinates of current train stations and use this data to discover nearby businesses and travel times.

* Train Station Patronage
    * Provider: Public Transport Victoria
	* Format: Excel sheet
	* License: Creative Commons Attribution (CC BY 4.0)
	* Usage: Extract the number of train lines serving each train station and the number passengers boarding.
*	Existing establishments and their current ratings
	* Provider: Foursquare
	* Format: API
	* License: Proprietary, Licensed according to the Foursquare Terms and Conditions
	* Usage: Determine current establishment within walking distance of the stations and their current ratings
*	Travel times and road traffic data
	* Provider: Mapbox
	* Format: API
	* License: Proprietary, Licensed according to the Mapbox Terms and Conditions
	* Usage: Determine travel time between current establishments and the train station along with travel times between the station and the Melbourne CBD
