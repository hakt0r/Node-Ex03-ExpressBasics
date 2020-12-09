# Express basics

## 1. Basic
  - Install the nodemon package globally 
    (you're going to need it, more and more)

  - Initalize an npm package here (in the exercise folder)
  - Install express
  - Add an index.js file
  - import express, create an app, and listen on port 4444
  - run it with nodemon (nodemon index.js)
  - direct your webbrowser to http://localhost:4444/

## 2. Static
  - Create a public folder
      - Add an index.html file containing some Hello World
  - Use the express.static plugin to serve the public directory

## 3. Dynamic
  - Add a route '/test.html' that returns a basic "dynamic"
    html page that takes in a (req.query.name) and responds
    with a basic html page saying Hello ${name}

## 4. Post
  - Create a POST route '/echo/'
  - make sure you use express.json()
  - the route should respond with whatever it finds
    in res.body
  - try your post route using a simple
    html/javascript from inside your "public" directory 