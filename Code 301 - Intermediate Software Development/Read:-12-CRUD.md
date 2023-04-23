## Status Codes Based On REST Methods

- In your own words, describe what each group of status code represents:

- 100’s = An informational response indicating that the request was received and understood, and that the client should proceed with its request.

- 200’s =A success response indicates that the request was successful and the server was able to return the requested data.

- 300’s = A redirection response indicating that the requested resource has moved or changed, and the client should follow the redirection instructions provided by the server.

- 400’s = A client error response indicates that the request was invalid or could not be processed by the server due to an error in the request.

- 500’s = A server error response indicates that the server was unable to fulfill the request due to an error on the server side.

- What is a status code 202?

Status code 202 indicates that the request has been accepted for processing, but the processing has not yet been completed.

- What is a status code 308?

Status code 308 indicates that the requested resource has been permanently moved to a new URL.

- What code would you use if an update didn’t return data to a client?

If an update didn't return data to a client, a status code 204 (No Content) would be appropriate to indicate that the request was successful, but there is no content to return.

- What code would you use if a resource used to exist but no longer does?

If the resource once existed but no longer exists, a status code of 410 (Gone) would be appropriate to indicate that the resource is no longer available and has been intentionally deleted.

- What is the ‘Forbidden’ status code?

The 'Forbidden' status code is 403, which indicates that the client does not have permission to access the requested resource. This can happen if the client is not authenticated or does not have the necessary authorization to access the resource.

## Build A REST API With Node.js, Express, & MongoDB - Quick - First 20 minutes

- Why do we need to pull our MongoDB database string out of our server and put it into our .env?

For security reasons, we need to extract the MongoDB database strings from the server and put them in the .env file. This helps to prevent our database credentials from being exposed in our code and shared publicly.

- What is middleware?

Middleware is software that acts as a bridge between different systems, allowing them to communicate and exchange data. In the context of Node.js and Express, middleware functions are used to process incoming requests and prepare them for the appropriate route handlers.

- What does app.use(express.json()) do?

app.use(express.json()) is a middleware function in Express that parses incoming requests with JSON payloads. It ensures that incoming requests with JSON data can be properly processed by our application.

- What does the /:id mean in a route?

The /:id in the route is a URL parameter that captures a dynamic value from the URL. In this case, the :id represents the unique identifier of a resource in our API.

- What is the difference between PUT and PATCH?

Both PUT and PATCH are HTTP methods used to update resources in a REST API. PUT is typically used to replace an entire resource with a new version, while PATCH is used to update a portion of a resource without replacing the entire resource.

- How do you make a default value in a schema?

To set a default value in a schema, you can use the default keyword when defining a field. For example: name: { type: String, default: 'John Doe' }.

- What does a 500 error status code mean?

A 500 error status code means that there was an error on the server side that prevented it from fulfilling the request. This could be due to a bug in the server code, an issue with the database, or other factors.

- What is the difference between a status 200 and a status 201?

The main difference between a status 200 and a status 201 is that 201 indicates that a new resource has been successfully created, while 200 simply indicates that a request has been successfully processed.

## Things I want to know more about
