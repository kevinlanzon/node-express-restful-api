A RESTful API Using Node and Express
-------------------

Here is an overview of the routes we will require, what they will do, and the HTTP Verb used to access it.

Route               HTTP Verb Description

/api/beers          GET       Get all the beers.
/api/beers          POST      Create a beer.
/api/beers/:beer_id GET       Get a single beer.
/api/beers/:beer_id PUT       Update a beer with new info.
/api/beers/:beer_id DELETE    Delete a beer.

This will cover the basic routes needed for an API. This also keeps to a good format where we have kept the actions we need to execute (GET, POST, PUT, and DELETE) as HTTP verbs.
