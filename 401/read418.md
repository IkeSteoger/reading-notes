# 401 Reading 18

## AWS: API, Dynamo and Lambda

### What is Amazon API Gateway?

Its a managed service that allows developers to define the HTTP end points of a REST API or a WebSocket API and connect those endpoints with the corresponding backend business logic.

### Why is Amazon API Gateway an important part of the Serverless ecosystem?

The API gateway is the piece that ties together serverless functions & API definitions.

### How does API Gateway integrate with other AWS services?

It can run Lambda functions to generate HTTP API responses.  
It can publish SNS notifications when the HTTP API endpoint is accessed.  
It can provide authentication and authorization for the HTTP APIs.

### What are the some benefits of using Amazon API Gateway?

EFficient API development, performance at any scale, cost savings at scale, easy monitoring, flexible security controls, RESTful API options

### What two API types might you choose from?

RESTful APIs & WEBSOCKET APIs

### What is DynamoDB?

Its a hosted NoSQL database offered by AWS.

### Under what circumstances would you recommend DynamoDB over MongoDB?

If your business already relies on AWS services, then DynamoDB is probably the best option for you. It'll be easy to deploy, maintain, and integrate with your current infrastructure. (blog.panoply.io)

### Explain to a non-technical friend how DynamoDB works

DynamoDB sort of works like holding all your information in a warehouse you can access via the internet.

### What is Dynamoose?

Its the modeling tool for DynamoDB, basically like Mongoose for MongoDB

### What are some key features of Dynamoose?

Type safetly, High level API, easy to use syntax, callback & promise support

### What are your learning goals after reading and reviewing the class README?

Hoping that this second round of NoSQL will help it stick better!
