# MarsWSsubmission

# web-scraping-challenge submission part 3
link for repo with full activity, flask application code, .py files, and index.html files. https://github.com/ImmaDadTho/web-scraping-challenge

In this activity I build a web application that scrapes various websites for data related to the Mission to Mars and displays the information in a single HTML page, and using the application creates a database in MongoDB and stores the information that was scraped in a table. There are two parts to this ativity the first part is `scraping` the second part is `MongoDB and Flask application`.

This repo conatins the jupyter notebook with all the scraping data, urls, and dictionaries that will be used for the html application.

# Scraping

I started by creating a jupyter notebook file to scrape and analyze different information pertaining to the mission to mars, the information gathered are as follows:


* Scraping the Mars News Site and collecting the latest News Title and Paragraph Text. 
* Use splinter to navigate the site and find the image URL for the current Featured Mars Image.
* Visit the Mars Facts webpage and use Pandas to scrape the table containing facts about the planet.
  * Use Pandas to convert the data to a HTML table string.
* Visit the astrogeology site to obtain high-resolution images for each hemisphere of Mars.
  * Use splinter to click each of the links to the hemispheres in order to find the image URL to the full-resolution image.
  
  
# Images of final Html page 

## Featured image and Mars Vs. Earth Facts
This image shows the featured image scraped and a table with facts comparing Mars and Earth that was scraped.
![Alt Text](screenshots/Fimage_Facts_news.jpg?raw=True "Title")

## Image of the four Hemispheres of mars
This image shows the four hemispheres of Mars and the respective names.
![Alt Text](screenshots/marsHemispheres.jpg?raw=True "Title")

## Image of header title and scrape button 
This image shows the Title of the the page and inside of the Title area a button labeled "Interstellar download" that begings scraping when pressed and returns the scrape data to the Html.
![Alt Text](screenshots/scraperbutton.jpg?raw=True "Title")
