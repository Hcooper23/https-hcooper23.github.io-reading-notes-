## Review: ES6 Classes

- Classes are a template for creating ____.

Objects

- Can a class declaration be hoisted?

No, class declarations in JavaScript are not hoisted. Unlike function declarations, class declarations are not moved to the top of the code. Therefore, if you try to access the class before it is declared, you will encounter a ReferenceError.

How would you describe a constructor and contextual “this” to a non-technical friend?

Think of a constructor as a blueprint for creating objects. Just like a blueprint defines the structure and properties of a house, a constructor defines the structure and properties of an object. It sets the initial state and behavior of the object. For example, if the constructor has a property called "name," when you refer to "this.name," it means the name property of the specific person object. "this" is like a placeholder that represents the object itself and allows it to access its own data and perform actions specific to that object. So, in simpler terms, a constructor is like a blueprint for creating objects, and "this" is a way for the object to refer to itself and access its own properties and behavior.

## Using Express Routing

- Within Express, what does routing refer to?

In Express, routing refers to the process of defining endpoints (URL paths) and handling incoming requests to those endpoints. It involves mapping specific URL patterns to corresponding functions or handlers that will process the request and send back an appropriate response.

- What is the difference between a route path and a route method?

In Express, a route path is a string that defines the matching pattern for a specific endpoint or route, allowing for parameterized and hierarchical routing.
It specifies the structure of the requested URL and can include dynamic segments represented by parameters. A route method, on the other hand, refers to the HTTP method associated with a particular route, such as GET, POST, PUT, or DELETE.
Each routing method has a specific purpose, such as retrieving data, submitting data, updating data, or deleting data on the server. By combining route paths and route methods, Express can match incoming requests to the appropriate route handlers based on both the requested URL structure and the specified HTTP method.

- When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?

The next parameter is added to a route handler or middleware function in Express to pass control to the next middleware or route handler in the chain. It is appropriate to include next when you want to delegate control to subsequent functions in order to perform additional operations or processing. If next has been passed to your middleware, it is your responsibility to invoke it by calling next() within your middleware function. By calling next(), you ensure that the request continues to flow through the subsequent middleware functions or reaches the final route handler. Neglecting to call next() will result in the request being left hanging, potentially causing it to timeout or fail, as subsequent middleware or route handlers won't be executed.

## Express Routing

- What is an Express Router?

An Express Router is a feature in Express that enables modular and organized routing in an application. It acts as a separate middleware that can be mounted on a specific path in the main Express application. With an Express Router, related routes and middleware can be grouped together, improving code organization, reusability, and maintainability. You can create an Express Router using the express.Router() method and define routes and middleware specific to that router using its methods like .get(), .post(), and .use(). By mounting the router using app.use(), and specifying the desired path, the router's routes, and middleware become accessible and can be integrated into the main application's routing structure, allowing for a more structured and modular approach to routing in Express.

- By what mean do we initialize express.Router() in an express server?

In the Express server, you can use express to initialize the Express Router.Router() method. This method returns an instance of an Express Router that you can use to define routes, middleware, and other functionality specific to that router.

- What do we use route middleware for?

Route middleware in Express is used to perform actions specific to certain routes or groups of routes. It enables tasks such as authentication, request validation, logging, error handling, and response formatting to be executed before or after the route handler. By separating concerns and delegating common functionalities to middleware, code organization, reusability, and maintainability are improved in Express applications.

## Things I want to know more about
