# TG-Pre-Work

## When we hit https://www.techtonicgroup.com/ what happens? Don’t focus too much on architecture (Monolithic, SOA, Microservices, etc.). Try to focus more on how the web functions.
 When I click a link on a web page, submit a form, or run a search, an HTTP request is sent from my browser to the target server which is https://www.techtonicgroup.com/  and then response to a request would contain the requested resource (e.g. a new HTML page, or an image, etc...) displayed on my browser.
## From start to finish how does that data reach you to be rendered in the browser?

Web browsers communicate with web servers using the HyperText Transfer Protocol (HTTP). When you click a link on a web page, submit a form, or run a search, an HTTP request is sent from your browser to the target server.

The request includes a URL identifying the affected resource, a method that defines the required action (for example to get, delete, or post the resource), and may include additional information encoded in URL parameters (the field-value pairs sent via a query string), as POST data (data sent by the HTTP POST method), or in associated cookies.

Web servers wait for client request messages, process them when they arrive, and reply to the web browser with an HTTP response message. The response contains a status line indicating whether or not the request succeeded (e.g. "HTTP/1.1 200 OK" for success).

The body of a successful response to a request would contain the requested resource (e.g. a new HTML page, or an image, etc...), which could then be displayed by the web browser.

## What code is rendered in the browser?

By default the rendering engine can display HTML and XML documents and images.
## What is the server-side code’s main function?

The main functions is validating submitted data and requests, using databases to store and retrieve data and sending the correct data to the client as required.

## What is the client-side code’s main function?

 Running in the browser and rendered web page.

## How many instances of the client-side assets (HTML, CSS, JS, Images, etc.) are created?

one per connection

## How many instances of the server-side code are available at any given time?

depends how much resource you dedicated to it.

## What is runtime?

Runtime is the period of time when a program is running

## How many instances of the the databases connected to the server application are created?
one connection.
