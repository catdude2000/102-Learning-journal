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

### Class 1-3 Notes

code lives in class repo, video here once processed:

"rm -rf (foldername)" to remove files in terminal

cp = copy
-r = recursive

"next" with nothing in it "()" in appget error response passes it to next middleware, message can be be put in "('message')"

don't put app.use'*' 404 before other responses, or they wont be read

app.use incorporates post put patch instead of app.get only doing get

root level index.js file for entry, specified in packjson

module.exports = { start, app } is an example of exporting from a server file, object restructuring in index calls this (I think)

tests need async

imbed image in md with ![image](path)

yml helps autodeploy and shows actions (on tests?) for TA

start script = (same as?) start command

class 2--------------------------------------------

redeploy after adding env variables

ask for sample data for wb interview

middleware is code that interacts with req res and next

can add individual middleware to specific routes, appuse puts it on all following

need run in npm run if anything but test or start

class 3-------------------------

integration tests tests multiple units of code, unit tests one unit of code

postgres is a db used with a postgresSQL dialect

sequelize: ORM. (object-relational mapping or mapper) Sequlize is to postgres as mongoose is to mongo

sqlite3: sqlite is ORM we will use specifically to TEST our DB - avoids side effects

sequelize CRUD create(), find() (or findOne()), Update(), Destroy()

"\c api-app" connects to api-app server in postgres

SELECT * (everything) FROM

customize config.json

cheat sheet in class 3 repo readme

sqlize docs model querying basics
