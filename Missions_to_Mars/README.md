# Mission to Mars - Web Scraping 

Build a flask web application that scrapes various websites for data related to the Mars Mission and displays the information in a single HTML page.

* [Background](#background)
* [Jupyter Notebook](#nb)
* [Technologies Used](#technologies)

##  <a name="background"></a>Background
Scrapping
 *NASA Mars News
	Script collects the latest News Title and Paragraph Text.
 *JPL Mars Space Images - Featured Image
	Script finds the image url for the current Featured Mars Image and assigns the url string of the full size image.
 *Mars Weather
	Script visits the Mars Weather twitter account and scrapes the latest Mars weather tweet.
 *Mars Facts
	Script visit the Mars Facts webpage and uses Pandas to scrape the table containing facts about the planet including Diameter, Mass, etc.
 *Mars Hemispheres
	Script visits the USGS Astrogeology site and obtains the full resolution images for each of Mar's hemispheres.

Url used for Web Scrapings are : [here]<https://mars.nasa.gov/news/?page=0&per_page=40&order=publish_date+desc%2Ccreated_at+desc&search=&category=19%2C165%2C184%2C204&blank_scope=Latest>. Second<https://www.jpl.nasa.gov/spaceimages/?search=&category=Mars>
 ,Third<https://twitter.com/marswxreport?lang=en>,Fourth<https://space-facts.com/mars/>,Fifth<https://astrogeology.usgs.gov/search/results?q=hemisphere+enhanced&k1=target&v1=Mars>


##  <a name="nb"></a>Jupyter Notebook

For this project, I used jupyter notebook to render and display the results of this analysis. You can view the notebook here:

<https://github.com/PunamSonawane/web-scraping-challenge/blob/master/Missions_to_Mars/mission_to_mars1.ipynb>
The notebook is also available inside this repository [here](.Missions_to_Mars/mission_to_mars1.ipynb).

##  <a name="technologies"></a>Technologies Used

* Python
* HTML/CSS
* Pandas library
* Splinter library
* Flask
* Beautifulsoup 
* PostgreSQL 
* Jupyter Notebook