# 301 Reading 06

## REST: REpresentational State Transfer

Roy Fielding was one of the authors of HTTP protocol and the creator of the REST architectural style.

The techniques we use in class don't work well when you need to be able to talk to all the machines of the entire world because they were NOT designed to be used the exact same way. Luckily, Roy Fielding had an idea for a solution.

Roy Fielding and his friends created HTTP protocol (Hypertext Transfer Protocol) to apply verbs to nouns and create a way for machines to transfer data. For example, a browser does an `HTTP GET` on the url you type in.

`GET` pulls the data onto application. When a machine `GET`s a resource, it will ask for machine readable data. But browsers `GET` a human-readable "representation" of the data.

`POST` is when one system needs to ADD something to another system.

`PUT` is when a system wants to REPLACE something in another system.

`PATCH` is a partial update version of `PUT`.

## Things I want to know more about

How did Mr. Fielding and his friends create this idea? Were there other similar creations or were they the pioneers in the field?
