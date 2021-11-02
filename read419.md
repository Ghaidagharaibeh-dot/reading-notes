# Spring and Sockets

### Using WebSocket to build an interactive web application
Websocket is basically a thin layer that works over TCP connections, by using what is knows as STOMP or Streaming Text Oriented Messaging Protocol in order to send and receive messages from and to the server.In Spring to create a websocket backend server we use Stomp-Websocket which is an external library that helps us to do so.In the front end we use SockJS client to send and receive messages to the backend server.

### Get started

- From https://start.spring.io select gradle and add Websocket dependency then click on generate. or Download and unzip the source repository, or clone it using Git: git clone https://github.com/spring-guides/gs-messaging-stomp-websocket.git

- cd into gs-messaging-stomp-websocket/initial

- Jump ahead to Create a Resource Representation Class.

- When you finish, you can check your results against the code in gs-messaging-stomp-websocket/complete.

