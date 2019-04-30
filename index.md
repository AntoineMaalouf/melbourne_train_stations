## Discovering Possible Opportunities Around Melbourne Train Stations

### 1. Introduction
Train stations can create business opportunities by leveraging the increased foot and road traffic that is created around train stations. By Analyzing different attributes of each train stations within the Melbourne metropolitan area, it’s possible to locate underserved stations and evaluate the possibility of developing new businesses in its vicinity. 

Melbourne is a fast-growing city with high levels of adoption of public transport among its residents. It’s estimated that a total of 565 million trips are taken every year using at least one form of public transportation with 240.9 million that includes at least one leg by train [1]. 

Rents around popular stations such as Melbourne Central and Southern Cross stations have increased exponentially while competition have increased. It’s possible to discover new underserved stations that can give a competitive advantage to property developers and certain businesses by filling the needs in underserved areas without paying the higher rents charged close to the CBD.

### 2.	Data
Several Data sources will be used to analyze the current situation of train stations along the lines serving the Melbourne CBD along with established businesses around them
* Train Station Geolocations and data
    * Provider: Department of Transport, Victoria, Australia
    * Format: GeoJSON
    * License: Creative Commons Attribution (CC BY 4.0)
    * Usage: Dataset contains several attributes that includes station names, location, train lines serving station, parking, and bike storage capacity

* Train Station Patronage
    * Provider: Public Transport Victoria
	* Format: Excel sheet
	* License: Creative Commons Attribution (CC BY 4.0)
	* Usage: Includes the average number of passengers boarding each station at different times during weekdays and total riders during weekends. The data also includes the results of a survey about the travel purposes and other modes of transports used during the same journey..
	
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
