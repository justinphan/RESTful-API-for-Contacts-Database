# resthub
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
