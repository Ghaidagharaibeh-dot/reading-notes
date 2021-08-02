## What does REST stand for?
representational state transfer 
State Transfer (REST) as an architectural approach to designing web services. REST is an architectural style for building distributed systems based on hypermedia. REST is independent of any underlying protocol and is not necessarily tied to HTTP. However, most common REST API implementations use HTTP as the application protocol, and this guide focuses on designing REST APIs for HTTP.
## REST APIs are designed around a 
resources
## What is an identifer of a resource? Give an example.

refers to the unambiguous reporting of research resources such as genes, organisms, tools, and reagents (such as antibodies). These resources should be reported within publications with enough information that reviewers and subsequent researchers can identify the exact strain or reagent used.

## What are the most common HTTP verbs?
- PUT
- POST
- GET	
- DELETE

## Give an example of a good URI.
customers/5 is the path to the customer with ID equal to 5


## What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
In general, an effective API design will have the following characteristics: Easy to read and work with

## What status code does a successful GET request return?
 status code 200 (OK).

 ## What status code does an unsuccessful GET request return?
404 (Not Found).
## What status code does a successful POST request return?
status code 201
## What status code does a successful DELETE request return?
 204 (No Content).