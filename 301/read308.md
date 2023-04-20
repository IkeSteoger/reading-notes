# 301 Reading 08

## API Design Best Practices

>What does REST stand for?
>>REpresentational State Transfer

>REST APIs are designed around resources.

>What is an identifier of a resource? Give an example.
>>its a URI that uniquely indentifies the resource. for example: `https://adventure-works.com/orders/1` (microsoft.com)

>What are the most common HTTP verbs?
>>`GET`, `POST`, `PUT`, `PATCH`, and `DELETE`

>What should the URIs be based on?
>>Nouns and NOT verbs

>Give an example of a good URI.
>>`orders` is good! `create-orders` is bad!

>What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
>>Exposing a large number of small resources. This is not good - try to avoid.

>What status code does a successful GET request return?
>>200

>What status code does an unsuccessful GET request return?
>>404

>What status code does a successful POST request return?
>>201

>What status code does a successful DELETE request return?
>>204
