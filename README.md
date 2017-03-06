Flask Heroku C2 Sample
====================

A simple Python Flask example application that's ready to run on Heroku.

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

## Development Setup

* `virtualenv venv`

* `source venv/bin/activate`

* `pip install -r requirements.txt`

* `python app.py`

## Deploy

* `heroku create`

* `git push heroku master`

## Setup 
set port to forward on (Defaults to 80):
* `heroku config:set PORT=80` 

set debug output to the log outlet (Defaults to True:
* `heroku config:set DEBUG=True` 

set forward C2 domain (Where to redirect to):
* `heroku config:set FORWARD_DOMAIN=cybersyndicates.com`

set redirector domain (Incoming domain name):
* `heroku config:set CURRENT_DOMAIN=tranquil-dawn-50102.herokuapp.com`


