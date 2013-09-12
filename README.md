# Le Pique-nique numérique

## Getting started

No database, just PHP & less CSS :

    npm install

Running the application :

    autoless css/less/ css/
    php -S localhost:8000


## Deployment

Setup :

    git remote add heroku git@heroku.com:piquenique.git
    heroku config:push

Deployment :

    git push heroku master