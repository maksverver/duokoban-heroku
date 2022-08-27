# Duokoban (Heroku)

## Deprecation notice!

This project is no longer maintained since Heroku shut down its free tier.

For a static version of the game that works (but does not support rating levels
or submitting custom levels), see: https://github.com/maksverver/duokoban-static

## Installation instructions

To install node_modules:

    npm install

To run locally:

    # Note: this uses the production database!
    export DATABASE_URL=$(heroku config:get DATABASE_URL)?ssl=true
    node server.js
