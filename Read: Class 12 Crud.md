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
