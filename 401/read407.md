# 401 Reading 07

## Bearer Authorization

### What is a JSON Web Token (JWT)?

JSON Web token is an open standard that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. (Jwt.io)

### When should we use JSON Web Tokens?

For authorization & information exchange.

### Claims are expected in which structural component of a JWT?

The payload!

### If I get a JWT and I can decode the payload, how can we call that secure?

When signed but not encrypted, everyone can read the contents but not change it without the private key. Encrypted means that there is a secret both parties exchanging the information would know, and the third party doesn't know the secret and thus cannot access the information.

### If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature

Both must know a shared secret.

### Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter

There is a box that can be sent between offices but it has a lock on it and only one key works, if someone gets ahold of that box and tries their own key, it won't work.

### Why use JWT?

They are a good way of securely transmitting information between parties because they can be signed, which means you can be certain that the senders are who they say they are. (auth0.com)

### JWT is Compact and self-contained. Describe how this is useful to a non-technical friend

Using our box analogy from earlier - the box is lightweight & easy to transport & requires nothing else except itself.

### What are the three components (the structure) of a JWT signature?

Header, Payload and Signature

## Things I want to know more about

How widespread is JWT? Are there other options?
