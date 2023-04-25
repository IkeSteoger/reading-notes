# 301 Reading 12

## CRUD

>In your own words, describe what each group of status code represents:
>>100’s = Informational codes, usually telling client that the header as been received and server will try to comply  
>>200’s = SUCCESS!!! Request was accepted.  
>>300’s = Redirect! Information not available at expected location, change request to new location  
>>400’s = Client error codes! Invalid requests, timeouts, wrong URI, missing authentication and more.  
>>500’s = Server Error codes! Often overwhelmed servers or unreachable servers behind proxies  

>What is a status code 202?
>>Accepted

>What is a status code 308?
>>Permanent Redirect

>What code would you use if an update didn’t return data to a client?
>>204

>What code would you use if a resource used to exist but no longer does?
>>308

>What is the ‘Forbidden’ status code?
>>403

>Why do we need to pull our MongoDB database string out of our server and put it into our .env?
>>To conceal our password to MongoDB

>What is middleware?
>>software that acts as a bridge between OS or database & applications, especially on a network

>What does app.use(express.json()) do?
>>It parses incoming JSON requests and puts the parsed data in `req.body`

>What does the /:id mean in a route?
>>its a unique ID added to each item in the data

>What is the difference between PUT and PATCH?
>>PUT is altering resources when the client transmits data that revamps whole resource - PATCH is for transforming the resources with client transmits PARTIAL data that will be updated without changing whole data

>How do you make a default value in a schema?
>>Something like `const schema = new Schema({ value: String })` would set up a default value, best to put in its own model

>What does a 500 error status code mean?
>>Server encounted an unexpected condition that prevented it from fulfilling request

>What is the difference between a status 200 and a status 201?
>>200 is "everything is OK!" while 201 is "Created a new resource"
