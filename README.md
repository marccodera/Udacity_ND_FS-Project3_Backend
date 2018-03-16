# Udacity_ND_FS-Project3_Build an Item Catalog Application

## Build an Item Catalog Application Project for Full Stack Nano Degree at Udacity
Last Update: March 16th 2018

Develop an application that provides a list of items within a variety of categories as well as provide a user registration and authentication system. Registered users will have the ability to post, edit and delete their own items.

## Requirements
Python 2.7.13 installed on the server.
PostgreSQL 9.5.11 installed on the server.
Internet connection from the server.

## Install
Copy “catalog” folder to the server drive, it must be a place that allows Python to be executed.

## Usage
Go to the catalog folder in your computer.
Launch application.py from python console or doubleclick it. It depends on how Python is configured on your server.
A webbrowser is launched where Item Catalog Application is showed, this is the URL: http://localhost:8000/

## JSON
The application has 2 JSON responses, one for categories and the other one for items, you can find the JSON using: http://localhost:8000/catalog/<category>/items/JSON and http://localhost:8000/catalog/categories/JSON

## Files in folder
Originally the content of the Catalog folder is:
```
\catalog\ ...
  \application.py
  \client_secrets.json
  \database_setup.pyc
  \README.md   
  \static\ ... (for the css style files)
  \catalog.db
  \database_setup.py
  \lotsOfCategories.py
  \README.txt
  \templates\ ... (for the HTML template files)
```

## Author
Marc Codera Campos

Contact
For information, bugs, feature requests, submit patches or other things related to this application:
* e-mail: marc.codera@gmail.com
* e-mail subject: [Item Catalog Application]YourSubject