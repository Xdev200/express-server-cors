![npm(scoped)](https://img.shields.io/badge/Github-https%3A%2F%2Fgithub.com%2FXdev200%2Fexpress--server--cors-blue)
![npm(scoped)](https://img.shields.io/badge/npm%20package-1.0.0-green)
![npm(scoped)](https://img.shields.io/badge/Twitter-https%3A%2F%2Ftwitter.com%2Fxdev__200-blue)


# Express-Server-CORS

> A library that creates an express server with cors.

## Installation

$ npm install --save @xdev200/express-server-cors

## Usage

const app = require('@xdev200/express-server-cors')

app.get('/',(req,res)=>{
    res.send('Hello World');
})