# Weather_Buddy
This is a weather app implementation, using the Flask (Python) framework.

## Table of contents
* [General info](#general-info)
* [Setup](#setup)

## General info
In order to run the program in your local environment, remember to fill in your personal information for the database and API_code to access the 
information at the openweathermap website.

The informations about the extensions used in python are in the requirements.txt file, here is what I added to my environment:

* Bootstrap-Flask 
* mysql-connector-python 
* requests

## Setup

* cloning repository
```
$ git clone https://github.com/CristianoR12/Weather_Buddy.git
```
* Prepare the virtual environment:
```
# Linux
sudo apt-get install python3-venv    # If needed
Activating: python3 -m venv env
```

* Enter your IDE (e.g. VSCode) - in case it is the VSCode
```
python -m pip install --upgrade pip
python -m pip install flask
```

* Install all requirements:
```
pip install -r requirements.txt
```

* Fill in the information for the database and your API_key(substitute the field {YOUR_API} in the URL)
 
* Start project
```
python3 -m flask run
```





