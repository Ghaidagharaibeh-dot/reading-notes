# WRRC and Java

# The HTTP Request Lifecycle

- Step 1: Local Processing
After entering the URL in your browser and xtract the schema of the request the Irl look like :
<protocol>://<host><:optional port>/<path/to/resource><?query>

and when browser get's the goals the browser try to resolve an IP address f

- Step 2: Resolve an IP

if browser does not find the IP address locally it will try to resolve it by hitting DNS servers with a DNS request using UDP protocol that will grab the IP address and send it back to the browser then if browser successful DNS request IP address will be store in the DNS cache.

- Step 3: Establish a TCP Connection

in order to send and request data from the server you need to establish a TCP connection to the server the client will need to complete a three-way handshake where both the server and the client have established a connection with received acknowledgements.

- Step 4: Send an HTTP Request

When the browser gets the response, it typically renders it on screen. The HTTP request is now done.

- Step 5: Tearing Down and Cleaning Up

# HTTP Request in Java

 to send an HTTP request in java  using the built in class HttpUrlConnection which replaced in JDK11 with HttpClient API,and to do an HTTP request we will build the request object using HttpRequest.(Builder or by calling HttpRequest.newBuilder())

 HttpRequest.newBuilder(request, (name, value) -> !name.equalsIgnoreCase("Foo-Bar"))
and  can be done as following

- Set up the URI
- Specify the method
We can choose among all HTTP methods (GET,POST,PUT,DELETE)
- Setting the HTTP protocol version
- Setting the Headers
We can specify any additional headers to our request.

- Setting a timeout
This is the time we wait for the request to complete.