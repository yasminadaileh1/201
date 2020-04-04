# Node, Express, and APIs

## Node.js

what is node.js?
**node.js** have different definitions such as :
- JavaScript runtime built on Chrome’s V8 JavaScript engine, &ldquo; project's Home Page &rdquo; .
- event-based, non-blocking, asynchronous I/O runtime that uses Google’s V8 JavaScript engine and libuv library, &ldquo; Stack Overflow &rdquo; .

Both of the definitions mintioned the **V8 JavaScript engine** it is an open-source JavaScript engine that runs in Google Chrome and other Chromium-based web browsers, including Brave, Opera, and Vivaldi. and responsible for compiling JavaScript directly to native machine and it has various features, such as:
* file system API.
* HTTP library.
* number of operating system–related utility methods.

I think we can see the output of the js file in the terminal window by using node and it comes bundled with a package manager called npm.

to install Package Globally type in your terminal :
 **npm install -g jshint** 
 to install Package Locally type in your terminal inside file :
 **npm init -y** 
 This will create and auto-populate a package.json file in the same folder.

 ### JavaScript on the Server
 Node as stack overflow mention its event-based, which means that everything that happens in Node is in reaction to an event. All about request and response the server will execute the callback and continue working on the original request.
 ![image](https://dab1nmslvvntp.cloudfront.net/wp-content/uploads/2012/10/1516152673node_event_loop.png)
