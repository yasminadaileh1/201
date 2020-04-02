#  Heroku Deployment

## Node.js
**Node.js** is an opining source  written in *JavaScript* but we need o install it. <img src="/reading-note/image/Capture.PNG">
We will use Node.js for our project because it is an open source, cross-platform runtime environment, allows you to build server-side
networking applications.

Make it worldwide
By using Heroku cloud application platform Create your project directory. And after that create the server.js file inside of it. So everyone could see how awesome you are as a web developer

but we need to declare  
var http = require("http");
var fs = require("fs");
var path = require("path");
var mime = require("mime");


We need to create the package.json file for that purpose. It will contain project related information:

* name
* version
* description
* dependencies
* mime

**Heroku Deployment**
Heroku platform use git as the primary means for deploying applications,
when you create an application on Heroku, it associates a new git remote, named heroku, with the locally git repository for your application. 
Build

