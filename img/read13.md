# Update/Delete

a **client** (usually a web browser) sends a request to a **server** (most of the time a web server), using the HTTP protocol. The server answers the request using the same protocol.

![client-server](img/client-server.png)

An HTML form on a web page is nothing more than a convenient user-friendly way to configure an HTTP request to send data to a server. This enables the user to provide information to be delivered in the HTTP request.

On the client side: defining how to send the data
All of elements attributes are designed to let you configure the request to be sent when a user hits a submit button
The two most important attributes are:
* action.
* method.

The **action** attribute defines where the data gets sent. If this attribute isn't provided, the data will be sent to the URL of the page containing the form — the current page.

The **method** attribute defines how data is sent. The HTTP protocol provides several ways to perform a request; HTML form data can be transmitted via a number of different methods, the most common being the GET method and the POST method.

HTML form data can be transmitted via a number of different methods:
* GET method : method used by the browser to ask the server to send back a given resource: "Hey server, I want to get this resource
* POST method : It's the method the browser uses to talk to the server when asking for a response that takes into account the data provided in the body of the HTTP request: "Hey server, take a look at this data and send me back an appropriate result."

After submitting the form:

1. Open the developer tools.
2. Select "Network"
3. Select "All"
4. Select "foo.com" in the "Name" tab
5. Select "Headers"

If you need to send a password (or any other sensitive piece of data), never use the GET method 
If you need to send a large amount of data, the POST method is preferred 

