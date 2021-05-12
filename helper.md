## NodeJS

NodeJS enables us to create backend using JavaScript. It enables us to work with JavaScript outside browser, be it as a desktop application or reach lower level system. Even Atom editor of Mac is based on NodeJS.

**Installation Steps:**
- Download Windows installer from [https://nodejs.org/en/](here)
- Choose the LTS version (On the left)
- Run installer (.msi file) and restart computer
- Confirm installation using node --version

**Using NodeJS**
- node index.js (runs the JS file using Node)

**Using Native Node Modules**
`const fs = require("fs")`
this line of code will import express module which is a native node module

**NPM and External Node Modules**
`npm init` - Sets up package for us asking for project details and creates package.json file
`npm install superheroes` - will install the external package superheroes which needs to be added in require statement

## Express
Express is a framework that helps to structure NodeJS code for web application. it makes you write less repititive code.

**Installation**
`npm install express`
Once installed can be imported in the code by `const express = require("express")`
Then we do `const app = express()` - this is a function that represents express module
`app.listen(3000)`

**Complete steps**
- create a new directory
- touch a new file server.js in it
- initialize npm with server.js as starting point
- npm install express
- add require('express') into the code


## NodeJS Challenge

Make a new folder called Calculator on your Desktop
Change Directory to this new folder
Inside the Calculator folder, create a new file called calculator.js
Set up a new NPM package
Open the project folder in Atom 
Using NPM install the express module
Require express in your calculator.js
Setup express
Create a root route get method with app.get()
Send the words Hello World from the root route as the response
Spin up our server on port 3000 with app.listen
Run server with nodemon
