# CRUD

_________________________________________

#### In your own words, describe what each group of status code represents:
* 100’s = Informational
* 200’s = Succesful
* 300’s = Redirection
* 400’s = Client Error
* 500’s = Server Error

___________________________________
### What is a status code 202?
* Accepted

### What is a status code 308?
* Permanent Redirect

### What code would you use if an update didn’t return data to a client?
* 204

### What code would you use if a resource used to exist but no longer does?
* 409

### What is the ‘Forbidden’ status code?
* 403
________________________________________________________
### Why do we need to pull our MongoDB database string out of our server and put it into our .env?

to have access to the databes in the server

### What is middleware?
functions that have access to the request object (req), the response object (res)

### What does app.use(express.json()) do?
recognize the incoming Request Object as a JSON Object

### What does the /:id mean in a route?
its a params

### What is the difference beween PUT and PATCH?
* PUT method uses the request URI to supply a modified version of the requested resource which replaces the original version of the resource
* PATCH method supplies a set of instructions to modify the resource.

### How do you make a defalut value in a schema?
* using mongoose command

### What does a 500 error status code mean?
* Internal Server Error

### What is the difference between a status 200 and a status 201?
* 200 request was received and understood and is being processed.
* 201 - Created A 201 status code indicates that a request was successful and as a result, a resource has been created
