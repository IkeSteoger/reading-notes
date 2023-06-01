# 401 Reading 13

## Message Queues

### Explain to a non-technical recruiter what the Chat Example (above) does

This is a basic chat application that makes use of Node.JS and Socket.IO.

### What proof of life are we getting on the backend from the above app?

`listening on *: 3000`

### Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?

`socket.broadcast.emit`

### What is a room and how might a room be useful?

You can have sockets `JOIN` specific rooms & then only `.emit` to that room, making them still work together in tandem but not interrupted or influenced by other rooms.

### How do you join a room?

In server:

```JavaScript
io.on("connection", (socket) => {
  socket.join("some room");
});
```

In client:

```JavaScript
io.to("some room").emit("some event");
```

### How do you leave a room?

```JavaScript
io.on("connection", socket => {
  socket.on("disconnecting", () => {
    console.log(socket.rooms); // the Set contains at least the socket ID
  });

  socket.on("disconnect", () => {
    // socket.rooms.size === 0
  });
});
```

### What is a Namespace and what does it allow you to do?

A Namespace is a communication channel that allows you to split the logic of your application over a single shared connection (also called "multiplexing"). (socket.io/docs)

### Each namespace potentially has its own what? (hint: 3 things)

Event Handlers, Rooms and Middlewares

### Discuss a possible use case for separate namespaces

- you want to create a special namespace that only authorized users have access to, so the logic related to those users is separated from the rest of the application
- your application has multiple tenants so you want to dynamically create one namespace per tenant

### What are your learning goals after reading and reviewing the class README?

My learning goals are to keep up & understand the content.
