## What is a status code 202?
202 Accepted - Often used for asynchronous processing. This code tells the client that the request was valid, but its processing will finish sometime in the future. The response body should include an URL to the finished resource with some information about when it will be available, or an URL to some monitoring endpoint that tells the client when the resource is available.
## What is a status code 308?
tells the client to use another URL to access the resource and not use the current URL anymore. It’s helpful when we have multiple endpoints for one resource, but don’t want to implement reading from all of them.
## What code would you use if an update didn’t return data to a client? 
204 No Content
## What code would you use if a resource used to exist but no longer does?
410 Gone
## What is the ‘Forbidden’ status code?
The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.

## What is middleware?
software that provides common services and capabilities to applications
## What does app.use(express.json()) do?
calls json which is a method that is built inside the express, it converts the objects to arrays or strings