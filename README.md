# Le Pique-nique numérique

## Getting started

No database, just plain PHP & LESS css.

### Requirements

This project requires PHP and NodeJS to compile LESS css.

PHP should be easy enough to install or already provided on your OS.

Regarding NodeJS, few hints for the newcomers :

- On OS X you should install NodeJS with [Homebrew](http://brew.sh) (`brew install nodejs`).
- On Linux and Windows, see [nodejs.org](http://nodejs.org) download section
or use your favorite package manager (ex. `apt-get install nodejs`).

Then install project dependencies (less, autoless, etc) :

    npm install

### Quick start

    ./node_modules/autoless/bin/autoless css/less/ css/
    php -S localhost:8000

## Deployment

Setup :

    git remote add heroku git@heroku.com:piquenique.git
    heroku config:push

Deployment :

    git push heroku master

1. http://piquenique.herokuapp.com
2. http://d2svtc8wj5w0di.cloudfront.net
3. http://piquenique.quebecnumerique.com
