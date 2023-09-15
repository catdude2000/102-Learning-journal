# Authentication

Readings  

## [Securing Passwords](https://thehackernews.com/2014/04/securing-passwords-with-bcrypt-hashing.html)

Explain to a non-technical friend how you would safely hash and store a password.  
Change it into unique characters, and store those in the database, instaed of the actual word.  

What is Bcrypt?  
An algorith to hash and salt passwords securely.  

Why might you use something like Bcrypt?  
To avoid bad actors getting passwords.  

## [Basic Auth](https://thehackernews.com/2014/04/securing-passwords-with-bcrypt-hashing.html)

What is Basic Authentication?  
A basic username and password request response process.  

What properties are necessary in the header of a Basic Auth request?  
Basic credentials

How are username:password in Basic Auth encoded?  
Base64, a method showing binary data in ASCII characters.  

## [OWASP auth cheatsheet](https://www.owasp.org/index.php/Authentication_Cheat_Sheet)

Define the authentication process to a non-technical recruiter.  
Process of using a name and password to verify someone's identity and what they can do on a website or app.  

How should your error messaging respond (both HTTP and HTML)? Why?  
With a generic message.  You don't want to giveaway specifics to the workings of the site.  

Bookmark this link also and consider OWASP fundamentals any time you interact with authentication. Applications developed with security in mind from inception have fewer vulnerabilities throughout their lifecycle.  

## Bookmark and Review

[bcrypt docs](https://www.npmjs.com/package/bcrypt)

### Additional Questions  

Looking ahead at this module’s course [schedule](https://codefellows.github.io/code-401-javascript-guide/curriculum/#module-2), What do you look forward to learning?  
Role Based Access Control.  

What are your learning goals after reading and reviewing the class [README?](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-06/)  
To be able to make my own basic authorization.  

## Things I want to know more about  

What other types of authorization are popular?  

- [Go to TOC](README.md)

### Class notes

401N Class 6 Notes

Encoding
-mutated data using a specfic sequence to modify it

npm i bcrypt base-64

Hash rounds default to 10 if not specified
