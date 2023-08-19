[[Status Codes Based On REST Methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)] 

In your own words, describe what each group of status code represents:

100’s = Tells client that the header part was received.

200’s = Tells client that the request was accepted.

300’s = Tells client that the request wasn't accepted at the location.

400’s = Tells client about invalid requests that weren't sent to server.

500’s = Tells client about indicate problems with overwhelmed servers or unreachable servers behind proxies.

What is a status code 202? This code tells the client that the request was valid, but its processing will finish sometime in the future.

What is a status code 308? This tells the client to use another URL to access the resource and not use the current URL anymore.

What code would you use if an update didn’t return data to a client?  

204 No Content

What code would you use if a resource used to exist but no longer does? 

410 Gone

What is the ‘Forbidden’ status code? 

The HTTP status code 403 Forbidden indicates that the server understood the request, but it refuses to authorize it. 


[[Build A REST API With Node.js, Express, & MongoDB - Quick](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw)] 

Why do we need to pull our MongoDB database string out of our server and put it into our .env?

By placing such sensitive data in a .env file, you separate it from your codebase, making it easier to manage and protect. The .env file is usually not shared in version control, reducing the risk of accidental exposure.

What is middleware?

Middleware in the context of web applications refers to a set of functions or code that sits between the request and the response in the application's processing pipeline.

What does app.use(express.json()) do?

In an Express.js application, express.json() is middleware that parses incoming JSON data from requests. I

What does the /:id mean in a route?

In a route, /:id is a parameterized segment that allows you to capture a dynamic value from the URL.


What is the difference between PUT and PATCH?

The PUT method is used to update or replace an entire resource at a specific URL. When you send a PUT request, you typically provide all the data needed to fully replace the existing resource with the new data you're sending while the PATCH method is used to make partial updates to a resource. 

How do you make a default value in a schema?

If you're referring to setting a default value for a field in a data schema (for example, in a MongoDB schema using Mongoose), you can do so by specifying a default property for that field when defining the schema.

What does a 500 error status code mean?

The HTTP status code 500 Internal Server Error indicates that the server has encountered an unexpected condition that prevented it from fulfilling the request. 

What is the difference between a status 200 and a status 201?

The HTTP status code 200 OK indicates that the client's request has been successfully received, understood, and processed by the server while the HTTP status code 201 Created is used to indicate that a new resource has been successfully created as a result of the client's request. 

