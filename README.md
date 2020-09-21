# Mission-to-Mars
Flask web application that scrapes various websites for data related to NASA's Mars Mission and displays the information on a single HTML page.

## Scraping

Within the `scraping.py` file:

NASA Mars News
- Script that collects the latest news title and paragraph text.

JPL Mars Space Images - Featured Image
- Script finds the image url for the current Featured Mars Image and assigns the url string of the full-size image.

Mars Facts
- Script visits the Mars Facts webpage and uses Pandas to scrape the table containing facts about the planet.

Mars Hemispheres
- Script visits the USGS Astrogeology site and gets the full resolution images and titles for each of Mar's hemispheres.

## MongoDB and Flask Application
The MongoDB can run locally. First, install MongoDB. Once MongoDB is installed, run the command mongod with bash and then proceed to use the files.

## Requirements
- Pandas
- Splinter
- PyMongo
- Numpy
- Flask
- requests
- beautifulsoup
- Flask-PyMongo
- Jinja
