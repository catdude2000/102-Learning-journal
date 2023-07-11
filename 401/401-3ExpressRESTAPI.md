# Readings: Express REST API

## Express is integral in backend programming

## Readings

### Review: [ES6 Classes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)

Classes are a template for creating ____.  
Creating objects  

Can a class declaration be hoisted?  
No  

How would you describe a constructor and contextual “this” to a non-technical friend?  
It specifies an object and what is a part of it.  

### [Using Express Routing](https://expressjs.com/en/guide/routing.html)

Within Express, what does routing refer to?  
"...how an application’s endpoints (URIs) respond to client requests."  
What response is given to a users command.  

What is the difference between a route path and a route method?  
Route methods provide the routing funcionality.  Route paths specify one specific route.  

When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?  
When imposing pre-conditions on a route, or to bypass remaining route callbacks, then pass control to subsequent routes.  

### [Express Routing](https://scotch.io/tutorials/learn-to-use-the-new-router-in-expressjs-4)

What is an Express Router?  
It's like a small express app. It provides us with the routing APIs like .use, .get, .param, and route.  

By what mean do we initialize express.Router() in an express server?  
app.use('/', router); (I think?)  

What do we use route middleware for?  
parameters.  req, res, next.  

## Reflection

What are your learning goals after reading and reviewing the class [README?](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-03/)

Getting comfortable with REST API servers, find out what Sequelize is, figuring out routes as they relate to testing.  

## Things I want to know more about  

When to use Express vs other methods.

- [Go to TOC](README.md)
