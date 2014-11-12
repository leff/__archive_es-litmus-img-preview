# es-litmus-img-preview

A way to serve images so that litmus can see them, while working on emails.
Uses Node.js and [Express 4](http://expressjs.com/) to serve up statics. Hosted on heroku.


## Running Locally

Make sure you have [Node.js](http://nodejs.org/) and the [Heroku Toolbelt](https://toolbelt.heroku.com/) installed.

```sh
$ git clone the repo
$ cd es-litmus-img-preview
$ npm install
$ npm start
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

## Deploying to Heroku

```
$ heroku create
$ git push heroku master
$ heroku open
```