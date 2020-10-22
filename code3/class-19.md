# HEROKU
## How to Node 
 for our project. Node.js is an open source, cross-platform runtime environment, which allows you to build server-side and networking applications. It's written in JavaScript and can be run within the Node.js runtime on any platform. 
 ### let's declare some variables:

* var http = require("http");
* var fs = require("fs");
* var path = require("path");
* var mime = require("mime");
The first one will give you the key to Node's HTTP functionality. The second one is for possibility to interact with the file system. The third one allows you to handle file paths. The last one allows you to determine a file's MIME-type. And it's not a part of Node.js, so we need to install third-party dependencies before using it. We need to create the package.json file for that purpose. It will contain project related information, such as name, version, description, and so on. For our project we will use MIME-types recognition, because it's not enough to just send the contents of a file when you use HTTP. You also need to set the Content-Type header with proper MIME-type. That's why we need this plug-in.

* **npm install** : 
It will create node_modules folder and place all the files inside of it. So, we resolve our dependencies and can return to our code.