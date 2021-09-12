# CRUD


*Status Codes Based On REST Methods*

Error codes based on what each group describes:

* 100's: These are informational codes which tell the client some information about the request.

* 200's: These are success codes which tell the client that the result of the request has been send.

* 300's: These are redirection codes which tell the client that what they requested is not available at that location anymore.

* 400's: These are client error codes, which tell the client there was a problem with his side of the request.

* 500's: These are server error codes which tell the client that there was some unexpected error within the server itself.

* Status code 202 is often used with asynchronous processing which tells the client that the server will respond in the near future.
Statues code 308 tells the client to use another URL to access the requested data.

* 204 No Content is used to indicate that the update didn’t return data to a client.

* 410 Gone is used when a resource used to exist but no longer does

* 403 is Forbidden status code.

* Build A REST API With Node.js, Express, & MongoDB - Quick
We need to add the mongoDB database string to the enviorment variables because of security reasons and because it depends on the deployment service.

* Middleware is a service that enables one or more kinds of communication or connectivity between two or more applications or application components in a distributed network.

* app.use(express.json()) is a method built in express to recognize the incoming Request Object as a JSON Object

* /:id is stored in the params and it is the best practice to represent IDs and keys.

* The main difference between the PUT and PATCH method is that the PUT method uses the request URI to supply a modified version of the requested resource which replaces the original version of the resource, whereas the PATCH method supplies a set of instructions to modify the resource.

* You can set a default value in the schema by assigning an object within the value of the property and inside that object you add the kay-value pair : default: 'something'.

* 500 is an internal server error.

* 200 meaning the data is sent to the client whereas 201 means something was success in the server but was not sent for an example : a new page has been created.