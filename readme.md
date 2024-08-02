# USED_CARS
This is a project based on a dataset of Used Cars and renders the listings based on the filters. In this project, we have used SimpleDB as our database, Flask for the backend and HTML Jinja Templates, and CSS for the front end. The main motive of the project is to dynamically fetch all the information from the SimpleDB Database and display it with interactive properties. 

## Usability
* Set the virtual environment by running the following command in the command prompt
> pip install venv (virtual environment name)
> virtual environment name can be of your choice

* Install boto by running the following command in the command prompt
> pip install boto

* app.py is the main Python file that you will run after installing the virtual environment.
* Lib directory contains Python libraries
* Static directory has all the images and CSS files used for UI
* Template directory has all the html files
* pyenv configuration source file contains the environment required for the flask.

## Tech Stack:
* HTML Jinja Templates (FrontEnd)
* Flask (Backend)
* SimpleDB (Database)

## Features of the Model:
* Retrieving the data from SimpleDB. 
* Making interactive UI for displaying more details.
* Inserting user data into the database.
* Retrieving the data from the database.
* Other features for searching the used car based on preferences as:
>Searching by the Listing ID

>Searching by model name of the car

>Searching with other attributes such as body type, exterior color, transmission, fuel type, etc.


## Dependencies:
1. boto.sdb
2. pandas
3. Flask Virtual Enviornment



