## Express Routing

### Routing refers to how an application’s endpoints (URIs) respond to client requests.

### You define routing using methods of the Express app object that correspond to HTTP methods; for example, app.get() to handle GET requests and app.post to handle POST requests. For a full list, see app.METHOD. You can also use app.all() to handle all HTTP methods and app.use() to specify middleware as the callback function.

## Express Middleware

### A series of functions that the request “goes through”.Each function receives request, response and next as parameters. Types of middleware: Application and Route.

### Application Middleware

- Error Handling

- Bringing in other routes

- Applies Defaults

- JSON, Body and Form Parsing

- Runs on every request

### Route Middleware

- Dealing with specific things for a route.

- Generally, things many routes would participate.

## Server Testing

### Generally, avoid starting the actual server for testing instead, export your server as a module in a library then, you can use supertest to run your tests.
