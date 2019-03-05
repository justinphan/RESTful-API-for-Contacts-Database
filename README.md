
This program is a example of a simple API using ExpressJs and MongoDb with CRUD functions for contacts.

RESTFul APIs are APIs that conform to the REST architecture style which defines a set of constraints and properties based on HTTP.The Commonest implementation of RESTFul web service is JSON API.

NodeJs is a run-time environment/engine created to run JavaScript on the server side.

ExpressJs is a framework for NodeJs. It will help to organize your application better.

MongoDB is an open-source database management system that useds a document-oriented database model which supports various forms of data. It is a NoSQL database. Instead of using tables and rows as in relational databases, the MongoDB architecture is made up of collections and documents. A record in MongoDB is a document which is a data structure composed of field and value pairs. MongoDB documents are similar to Json bu use a variant called Binary Json (BSON) to accommodate more data types.

We will implement the following endpoints

GET /api/contacts list all contacts
POST /api/contacts create new contact
GET /api/contacts/{id} retrieve a single contact
PUT /api/contacts/{id} update a single contact
DELETE /api/contacts/{id} delete a single contact

The results is tested by PostMan, a popular tool for testing and debugging API

Steps: 
1. Create a project directory
2. Initilize the NodeJS project with "npm init"
3. Create index.js file to import express, initialize the app, setup server port
4. Create api-routes.js to defined the api endpoints
5. Create a model using MongoDB to manage database layer. Mongoose is used as a Nodejs package for Mongodb modeling.
6. Create a controller Processes HTTP requests and defines available endpoints

SCREENSHOTS:
Model
![alt text](https://i.imgur.com/a8z28Vz.png)

Control
![alt text](https://i.imgur.com/4qXnOkS.png)

Posman
![alt text](https://i.imgur.com/iHXXUy5.png)
