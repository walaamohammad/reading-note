# What does REST stand for?
is an architectural approach to designing web services. REST is an architectural style for building distributed systems based on hypermedia. REST is independent of any underlying protocol and is not necessarily tied to HTTP
# REST APIs are designed around a _ resources___.
# What is an identifer of a resource? Give an example.
 has an identifier, which is a URI that uniquely identifies that resource. For example, the URI for a particular customer order might be:
# What are the most common HTTP verbs?
the uniform interface includes using standard HTTP verbs to perform operations on resources. The most common operations are GET, POST, PUT, PATCH, and DELETE.
![verbs](https://martinfowler.com/articles/images/richardsonMaturityModel/level2.png)
____________________________________________________
# What should the URIs be based on?
based on nouns (the resource) and not verbs (the operations on the resource).
# Give an example of a good URI.
https://adventure-works.com/orders
# What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
Network calls and other I/O operations are inherently slow compared to compute tasks. Each I/O request typically has significant overhead, and the cumulative effect of numerous I/O operations can slow down the system. Here are some common causes of chatty I/O.
# What status code does a successful GET request return? 
eturns HTTP status code 200 (OK).
# What status code does an unsuccessful GET request return?
404 not found
# What status code does a successful POST request return?
HTTP 201 created
# What status code does a successful DELETE request return?
the web server should respond with HTTP status code 204, indicating that the process has been successfully handled.

