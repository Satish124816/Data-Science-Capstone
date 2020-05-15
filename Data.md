###  **Data**

**To solve the problem, we need the following data:**  

* List of neighborhoods in Delhi. This defines the range of area of consideration in the project which is Delhi,capital city of India
* Latitude and longitude coordinates of each neighborhoods. These are needed in order to plot the neighborhoods on map and also to get the venues in each neighborhoods.
* Venue Data, which will be used to perform clustering on neighborhoods.

### Sources of Data and its extraction

* The neighborhood list data can be found in the following wikipedia page link (https://en.wikipedia.org/wiki/Neighbourhoods_of_Delhi). By web scraping we can extract the data from the page, using python requests and BeautifulSoup packages.

* The latitude and longitude(geographical coordinates) data of the neighborhoods can be extracted using the geocoder package of python.However a very few neighborhoods geographical coordinates are not found using geocoder package which can be separately found

* Lastly we will use FourSquare API to get venue Data of neighborhoods. Foursquare has one of the largest Database of more than 105 million places worldwide.

 

 

 

 

In this project we will make use of Data Science tools such as web scraping, working with Foursquare API, Data cleaning, Data wrangling, machine learning(e.g. K-means clustering), folium (map visualisation) and Matplotlib.  
 In next section we will discuss about Data Science Methodology.
