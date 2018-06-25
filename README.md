# Mongo-Scraper

## Overview
The mongo-scraper app is a web app that scrapes articles from the New York website and lets users save articles. read articles, leave comments, remove comments and delete articles. This is a fully functioning CRUD app built according to an MVC model. 

## How It Works
CREATE: Scrape articles by clicking the "Scrape Articles" button.

READ: Once articles are loaded, read full article by clicking the "Read Article" link in each article's panel. Save articles by clicking the "Save Article" button. All saved articles can be viewed at the "Saved Articles" page. 

UPDATE: Comments can be added on saved articles by clicking the "Add a Comment" button. Once the button is clicked a modal will prompt the user to leave a comment. As many number of comments can be created for a particular article as desired, and comments are displayed for all users to view. 

DELETE: Saved articles can be deleted by clicking the "Delete" button. Saved comments can be deleted by clicking the "Delete" button on the side of the comment. 

## Technologies Used
HTML
CSS
Javascript
Materialize
Node.js
Express.js
Handlebars.js
MongoDB
Mongoose
npm packages
body-parser
express
express-handlebars
mongoose
cheerio
request
Heroku (to host)