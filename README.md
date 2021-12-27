# WebPortfolio
This project showcases my data science projects on a deployed website.

Latest update: small color changes.


Table of Contents
Installation
Project Motivation
To Do
Instructions
Create Database for Content
Updating Database Content
File Descriptions
Licensing, Authors, Acknowledgements
Installation
The code requires Python versions of 3.* and general libraries available through the Anaconda package. In addition, psycopg2 for the PostgreSQL database, Flask, Werkzeug and gunicorn need to be installed to be able to deploy the website. Please refer to the requirements.txt file for more details on dependencies.

Project Motivation
I always wanted to have my own space where I can restore my projects in propper way, with links to their code. This site also helps me to keep track on my progress. 
To Do
TODO: See if cards are good choice
TODO: Check why root body etc are loaded multiple times
TODO: Check the dissalowence crawlers to index this website
TODO: add homepage button after resetting password
TODO: check if ninja is needed
 
File Description
The templates folder contains all html pages that will be accessible through the site. The static folder is made up of the images displayed on my website, the css stylesheet. app.py is the file which will render the website. database_feeder.py is the script that reads in the data from the Excel files into the database. 

Licensing, Authors, Acknowledgements TBC
