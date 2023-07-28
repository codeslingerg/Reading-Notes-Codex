[API Design Best Practices](https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design)

What does REST stand for?

***REST is an architectural style for building distributed systems based on hypermedia.***

REST APIs are designed around a ____.

***REST APIs are designed around resources, which are any kind of object, data, or service that can be accessed by the client.***

What is an identifier of a resource? Give an example.

***An identifier is a URI that uniquely identifies that resource.https://adventure-works.com/orders/1***

What are the most common HTTP verbs?

***The most common HTTP verbs are GET, POST, PUT, PATCH, and DELETE.***

What should the URIs be based on?

***Resource URIs should be based on nouns (the resource) and not verbs (the operations on the resource).***

Give an example of a good URI.

***Good URI is /customers is the path to the customers collection, and /customers/5 is the path to the customer with ID equal to 5***

What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

***Having a chatty web API means all web requests impose a load on the web server. It's best not to have one.***

What status code does a successful GET request return?

***GET should return HTTP status code 204 .***

What status code does an unsuccessful GET request return?

***Unsuccessful should return 404 (Not Found)***

What status code does a successful POST request return?

***A successful code should return HTTP status code 200***

What status code does a successful DELETE request return?

***If the delete operation is successful, the web server should respond with HTTP status code 204 (No Content).***
