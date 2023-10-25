# Ecommerce Mern stack project
## Environment Setup using node install node -v for version check

## Exprss.js setup using( npm init -y) and npm -v for version check , and do some edit in package.json = "main for sever load", "description","keyword".  install process of Expressjs : 
1. go to expressjs.com and paste " npm install express
"

## then make new folder name " src " and make a file (server.js) and expressjs ke niye aste hobe  server.js e.
const express = require('express')

const app = express()       ///= assign express to app

app.listen(3001, ()=>{
    console.log('Server is running at http://localhost:3001')
});          ///= to listen the app

## to run (serverjs) file . in terminal: write (node src/server.js)  
to stop server one way cmd+c;
