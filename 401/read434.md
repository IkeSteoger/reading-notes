# 401 Reading 34

## API Integration

### [Review API Server Build](https://codefellows.github.io/code-401-javascript-guide/curriculum/apps-and-libraries/api-server/)

### Explain the different between a query string parameter and a path parameter

Path params are used to identify a specific resource, while query params are used to filter and sort data.

### What would our API URL with a path id parameter be given the following information

- Domain: http://our-site.com
- v3
- model name: stuff
- id: things

[http://our-site.com/v3/stuff/things]

### We have created a dynamic API with an “interface”. Describe how that interface works to a non-technical friend

The interface allows someone who doesn't exactly know CRUD or the API endpoints to access them. This basically will allow you to access data, make changes, and other functionality, without having to have technical know how, just need to learn to use the interface.

### [Review Auth Server Build](https://codefellows.github.io/code-401-javascript-guide/curriculum/apps-and-libraries/auth-server/)

### Describe how you would use middleware to implement basic and bearer auth

You can import middleware to validate the "Authorization" + encrypted username:password for basicAuth to allow access. For bearerAuth you would need to make use of "Authorization" + the token, which would then allow access.

### Describe the handshake necessary to implement OAuth

You would create a middleware or a handshake to handle the OAuth implementation.

### Describe how Role Based Access Control works to a non-technical friend

Basically just like people with keys.  
Admin is a master key  
Editor is a key to all doors besides those that allow deletion  
Writer is a key to all doors besides those that allow updating  
User is a key to only the outside door and to just read  
No one else can get in.