# Bearer Authorization

## [Intro to JWT](https://jwt.io/introduction/)

What is a JSON Web Token (JWT)?  
A token format tha's used in authentication online.  

When should we use JSON Web Tokens?  
Easy to use and works on many things.  

Claims are expected in which structural component of a JWT?  
Payload.

## [Are JWTs Secure?](https://stackoverflow.com/questions/27301557/if-you-can-decode-jwt-how-are-they-secure)  

If I get a JWT and I can decode the payload, how can we call that secure?  
It still has to match the authorization.  

If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.  
Authorization data. (username and password, like a key-value pair)  

Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.  
It's as safe as sending a coded message seperately from a cipher with no instructions.  They need to be used together and you need to know how.  

### Video

## JWTs Explained

Why use JWT?  
to securely send information.  

JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.  
You can send it many different ways.  

What are the three components (the structure) of a JWT signature?  
header  
payload  
signature (for security)  

Bookmark and Review

[npm jsonwebtoken docs](https://www.npmjs.com/package/jsonwebtoken)

What are your learning goals after reading and reviewing the class [README?](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-07/)

To be able to understand what, besides hashing, makes authorization methods so different?  

## Things I want to know more about  

Can you customize the signature to make it more complex?  

- [Go to TOC](README.md)
