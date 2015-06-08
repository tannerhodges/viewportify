# Viewportify

A little site for generating visualisations of the screen reolutions or
viewports used by visitors to a site.

Try out [@philhawksworth](https://github.com/philhawksworth)'s original
version at [viewportify.hawksworx.com](http://viewportify.hawksworx.com).

## Local Development

```
npm install      # Install project dependencies
mongod           # Start your Mongo database
node server.js   # Run local server
```

View [localhost:5000](http://localhost:5000/) in your browser.

### Dependencies

- [Node](https://nodejs.org/)
- [MongoDB](https://www.mongodb.org/)

I recommend installing Node and MongoDB with (Homebrew)[http://brew.sh/]
(assuming you're on a Mac).

**Note:** [Foreman](http://ddollar.github.io/foreman/) is just for Heroku. You
can skip or delete if you don't need it.

## Hosting

If you want, you can deploy this bad boy to Heroku.

Check out this tutorial: [Getting Started with Node.js on Heroku](https://devcenter.heroku.com/articles/getting-started-with-nodejs)

When the time comes, use `git push heroku master`.

