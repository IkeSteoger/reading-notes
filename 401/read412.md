# 401 Reading 12

## Socket.io

### What is a Web Socket?

Its a computer communications protocol, providing full-duplex communication channels over a single TCP connection (wikipedia.org)

### Describe the Web Socket request/response handshake and what happens once the connection is established

The Handshake starts with an HTTP request/response, allowing servers to handle HTTP connections as well as WebSocket connections on the same port. Once established, communication switches to a bidirectional binary protocol which does not conform to the HTTP protocol (wikipedia.org)

### Web Sockets provide a standardized way for the server to send content to a client without first receiving a ____ from that client

Request

### What does the event handler io.on() do?

Adds a listener that will be fired when any event is emitted

### Describe some possible proof of life or proof that the code works as expected

[https://www.tutorialspoint.com/socket.io/socket.io_hello_world.htm]explains exactly how to do so

### What does socket.emit() do?

Sends a message to all connected clients

### What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0)

WebSocket is a technology that enables two-way real time communication between client and server. Socket.IO is a library that provides an abstraction layer on top of WebSockets (ably.com)

### When would you use Socket.IO?

When you want to work with vanilla web sockets but want to make it easy

### When would you use WebSockets?

For real time communication between server & client

### What are a couple of key takeaways from this video?

OpenSystemInterconnection model can be used for translation of data. And also data compression which can be used for all sorts of things, including video/audio streaming. Also encryption to enhance security. There are a ton of ways OSI makes things work better.

### Translate the gist of this video to a non-technical friend

Suppose you want to get a fruit from the market, but first you must establish its okay with a three way handshake: you go into the store and ask for fruit, the store replies and asks if this is the fruit you want, if the you accept, then the handshake is complete.
