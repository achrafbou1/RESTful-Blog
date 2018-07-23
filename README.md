# Application overview

An application that simulates a blog where everyone has the same privileges folllowing the 7 REST conventions.

## Installation

# Getting Started

To get the Node server running locally:
- Install Node from https://nodejs.org/en/download/
- Clone this repo
- Run `npm install` to install all required dependencies
- Run `node app.js` to start the server

# Code Overview

## Dependencies

- [express](https://github.com/expressjs/express) - The server for handling and routing HTTP requests
- [body-parser](https://github.com/expressjs/body-parser) - For parsing incoming body requests
- [ejs](https://github.com/tj/ejs) - For rendering views
- [express-sanitizer](https://github.com/markau/express-sanitizer) - To prevent the execution of malicious code
- [mongoose](https://github.com/Automattic/mongoose) - To easily manipulate the MongoDB database
- [method-override](https://github.com/expressjs/method-override) - To execute PUT and DELETE requests

## Application Structure

- `app.js` - The main application.
- `views/` - This folder contains ejs views that are used for dynamic rendering of movies through the IMDB API.
- `views/partials` - This folder contains secondary ejs views required for DRY code (header and footer).
- `public/stylesheets` - This folder contains the css files.


