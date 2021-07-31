# The Battle of the Neighborhoods: open  a pizza shop in Toronto
Capstone project for IBM Data Science Professional Certificate on Coursera.
***
## Project summary
__Goal__:
-To figure out the best locations for opening up a new pizza shop in Toronto City.

__Target Audience__: 
- Entrepeneurs, Business Owners, Stakeholders

__Datasets__:
- [1st Data](https://tinyurl.com/vehicle-foot-traffic): The most updated record of traffic signal vehicle and pedestrian volumes in Toronto City. 
- [2nd Data](https://tinyurl.com/toronto-mci): The most updated record of crime incidents reported in Toronto City provided by Toronto Police Services.
- [3rd Data](https://tinyurl.com/toronto-postal-code): The list of Toronto neighborhoods represented by postal codes and their boroughs. 
- [4th Data](https://developer.foursquare.com/): The popular or most common venues of a given neighborhood in Toronto. 


The followings are the step by step process for working with the project:

### 1. Web Scraping: Toronto Postal Codes

We will start the project by scraping the following Wikipedia page.
https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M

Objective:
- Obtain the data inside the html page containing a list of Toronto postal codes in the form of table and transform the data into a pandas dataframe!

You can see the process in [part1.Segmenting and Clustering Neighborhoods in Toronto.ipynb](https://github.com/as183789043/Coursera_Capstone/blob/master/part1.Segmenting%20and%20Clustering%20Neighborhoods%20in%20Toronto.ipynb)


### 2. Coordinate Retrieval: Toronto Postal Codes

Objective:
- Now, we will get the latitude and the longitude coordinates of each neighborhood in order to utilize the Foursquare location data later in the separate main project notebook.

You can see the process in [part2.Segmenting and Clustering Neighborhoods in Toron.ipynb](https://github.com/as183789043/Coursera_Capstone/blob/master/part2.Segmenting%20and%20Clustering%20Neighborhoods%20in%20Toron.ipynb)


### 3.  Segment & Cluster Toronto Neighborhoods

Objective:
- We will __explore__, __segment__, and __group neighborhoods__ into clusters to find similar neighborhoods in __Toronto City__. As far as this project is concerned, we will use the __Foursquare location dataset__ and use __Foursquare API__ to access it.

You can see the process in [part3.Segmenting and Clustering Neighborhoods in Toron.ipynb](https://github.com/as183789043/Coursera_Capstone/blob/master/part3.Segmenting%20and%20Clustering%20Neighborhoods%20in%20Toron.ipynb)

### 4. The Main Project Notebook

Objective: 
- Compile everything to acomplish the project's goal.



