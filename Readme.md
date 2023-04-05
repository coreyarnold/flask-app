# Flask-App

This is a basic example app. It is intended to show instrumentation with New Relic python agent and Browser agent auto instrumentation.

 * set New Relic license key in `newrelic.ini`
 * turn on Browser agent auto instrumentation by setting `browser_monitoring.auto_instrument = true`

## How to run
`pipenv install`
`pipenv shell`

`pip install flask`
`export FLASK_ENV=development`
`export FLASK_APP=app`

`pip install newrelic`

`flask run`


## References
This app follows the tutorial on [digitalocean](https://www.digitalocean.com/community/tutorials/how-to-make-a-web-application-using-flask-in-python-3). You will also need to setup a python environment using Homebrew, Pyenv, and Pipenv.
