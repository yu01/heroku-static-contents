# a sample of static contents on Heroku

## How to

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

or

    $ heroku create
    $ git push heroku master
    $ heroku open

## You can run on localhost

    $ npm install
    $ node app.js
    Server starting on http://0.0.0.0:3000

## Basic Authentication

    $ heroku config:set BASIC_AUTH_USERNAME=username
    $ heroku config:set BASIC_AUTH_PASSWORD=password
