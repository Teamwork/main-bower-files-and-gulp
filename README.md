Hassle-free third-party dependencies with Bower and Gulp
=========================                               

This repository was created for the [Hassle-free third-party dependencies](http://engineroom.teamwork.com/hassle-free-third-party-dependencies) blog post on [engineroom.teamwork.com](http://engineroom.teamwork.com).

# Set up

Prerequisites: [Node.js](http://nodejs.org/), [Bower](http://bower.io) & [Gulp](http://gulpjs.com).

You'll need to run these commands one time to set up the project ready:

1. `npm install`. This will install the `devDependencies` in `package.json` into the `node_modules` directory.
2. `bower install`. This will install the `dependencies` in `bower.json` into the `app/third-party` directory.

# Preprocess the dependencies

Run this initially and anytime after you add / remove / update a Bower dependency:

1. `gulp`. This will generate `app/third-party.css` and `app/third-party.js`.
2. Open / reload `app/index.html`