<h1 align="center">MyFlix-backend Documentation</h1>

# Objective

To build the server-side component of a “movies” web application. The web application will provide users with access to information about different movies,
directors, and genres. 
Users will be able to sign up, update their personal information, and create a list of their favorite movies.

# Feature Requirements

* Return a list of ALL movies to the user
* Return data (description, genre, director, image URL, whether it’s featured or not) about a single movie by title to the user
* Return data about a genre (description) by name/title (e.g., “Biography”)
* Return data about a director (bio, birth year, death year) by name
* Allow new users to register
* Allow users to update their user info (username, password, email, date of birth)
* Allow users to add a movie to their list of favorites
* Allow users to remove a movie from their list of favorites
* Allow existing users to deregister


# Technical Requirements

The API:

* must be a Node.js and Express application,
* must use REST architecture, with URL endpoints corresponding to the data operations listed above,
* must use at least three middleware modules, such as the body-parser package for reading data from requests and morgan for logging,
* must use a “package.json” file,
* must provide movie information in JSON format,
* must be tested in Postman,
* must include user authentication and authorization code,
* must include data validation logic,
* must meet data security regulations,
* source code must be deployed to a publicly accessible platform like GitHub,
* must be deployed to Heroku.

* The database must be built using MongoDB.
* The business logic must be modeled with Mongoose.
* The JavaScript code must be error-free.

# Built with:
* JavaScript
* Node.js
* Express
* MongoDB
* Mongoose

**Hosted on Heroku** [myFlix](https://backend-myflix.herokuapp.com)
