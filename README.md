# Mission-to-Mars

## Overview

This repository showcases the webscraping exercise utilizing beautiful soup, noSql Mongodb image scraping, flask connection and local html visualization. Additional changes were made to the page utilizing CSS.

In this repository, there is a series of files contributing to a Flask-rendered site that compiles information about ongoing Mars-related research. The files include -

* Scraping.py, which includes a set of functions that scrape each of the image and text-related components and stores the data in MongoDB
* App.py, which initializes the scraping functions and prepares the scraped data to incorporate into the Flask-generated site
* Index.html, which renders the web page in Flask
