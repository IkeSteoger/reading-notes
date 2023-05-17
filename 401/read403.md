# 401 Reading 03

## Express REST API

### Classes are a template for creating ____

Classes are a template for creating objects!

### Can a class declaration be hoisted?

No - they behave as if they are not hoisted.

### How would you describe a constructor and contextual “this” to a non-technical friend?

Its like a room full of boxes. `this` works within the box its found in. 

### Within Express, what does routing refer to?

Routing refers to how an applications end points AKA URIs respond to client requests (expressjs.com)

### What is the difference between a route path and a route method?

Route Paths are the actual path like `/person` but method is by how you are calling it, such as `get` `post` `put` etc

### When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?

When you have more than one callback function, it is important to provide the `next`.

### What is an Express Router?

Its a mini express application without all of the bells & whistles of an express application, just the routing stuff. (digitalocean.com)

### By what mean do we initialize express.Router() in an express server?

`const router = express.Router()`

### What do we use route middleware for?

Its a way to do something before a request is processed.

### What are your learning goals after reading and reviewing the class README?

Not README related but my learning goals are to ACTUALLY understand what is happening within the code, rather than just copying demo code.