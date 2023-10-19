# RESTful API

## Overview
This project details a REST API, created using Node.js and Express for routing. Postman was used to test the API endpoints. It allows users to view and add to a users list, visible from the webpage.
Additional functionalities include being able to update, delete, and view specific user information.

## Installing dependencies
Install Node.js from [Node Website](https://nodejs.org/en)

Verify the installation using
```
>>> Node -v
14.5.0
```

Install Express in the terminal using
```
npm install express --save
```

## Organization
index.js: App creates an instance of Express and establishes the port and /user route

routes: Router is called to retrieve, update, and delete data

controllers: Defines the routing logic and displays data on the webpage
