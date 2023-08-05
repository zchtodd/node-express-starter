# ExpressJS Starter Template

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/template/Vp8hse?referralCode=vimo)

This is boilerplate/starter project for quickly building RESTful APIs using Node.js and [Express](https://expressjs.com/), written in JavaScript.
It will help you get started with a simple to follow format with some examples for routes, logging and middleware.

## Features

- Express
- Morgan for http request logging
- Example route at /hello
- Example logger to create or redirect your logs to the service of your choice
- Example middleware to further expand to use for auth

## Project Structure

```
src\
 |--routes\         # Routes
 |--utils\          # Utility files
 |--app.js          # Express app
 |--index.js        # App entry point
```

## About

The server runs a simple Express API server

`/` returns `status: ok` 

`/hello` is returns `message: Hello World!`

Unknown endpoints are handled in a middleware file.

The `hello` route is defined  in the `helloRoute`   
