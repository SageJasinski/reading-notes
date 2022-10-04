# Readings

## Status codes based on REST methods

1. In your own words, describe what each group of status code represents:
    - 100’s = These codes are a client sided warning that the code will fail/run incorrectly

    - 200’s = These codes are also client sided and tell the client if the request is accepted

    - 300’s = Redirection codes that tell the client that resource isn’t in the expected location, they must then request it from the new location instead

    - 400’s = Client error codes alert that invalid requests are being sent to the server, caused by timeouts, wrong URI, missing authentication

    - 500’s = Server error codes, warn of overwhelmed servers, unreachable servers behind proxies, or trigger error exceptions on the server.

2. What is a status code 202?
    - An asynchronous processing of a request that denotes that it met all validation requirements

3. What is a status code 308?
    - Permanent Redirect, tells the client to use a new url to access the resource

4. What code would you use if an update didn’t return data to a client?
    - 204 No Content

5. What code would you use if a resource used to exist but no longer does?
    - 410 Gone

6. What is the ‘Forbidden’ status code?
    - 403 Forbidden

## Build A REST API With Node.js, Express, & MongoDB - Quick - First 20 minutes

1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?
    - Since the env is ignored it keeps the data private/locked

2. What is middleware?
    - Code that runs when the server gets a request but before it gets passed to the routes

3. What does app.use(express.json()) do?
    - Gets the server to accept json as a body instead of a post element

4. What does the /:id mean in a route?
    - Creates a parameter to get whatever is typed after the first /

5. What is the difference between PUT and PATCH?
    - patch only updates with what the user passes, none of the other information like PUT would do, replacing all of the subscriber information, in the videos example.

6. How do you make a default value in a schema?
    - By using the default keyword

7. What does a 500 error status code mean?
    - There is an error on your server, not the user’s fault

8. What is the difference between a status 200 and a status 201?
    - Status 201 means successfully created an object, while 200 means everything was successful
