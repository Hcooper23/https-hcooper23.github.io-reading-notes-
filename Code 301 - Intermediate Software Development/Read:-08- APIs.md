## API Design Best Practices

- What does REST stand for?

Representational State Transfer

REST APIs are designed around a ____. [RESTful web API design]( https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design)

REST APIs are designed around resources, which are any kind of object, data, or service that can be accessed by the client. REST APIs use a uniform interface, which helps to decouple the client and service implementations.

- What is an identifier of a resource? Give an example.
- What are the most common HTTP verbs?

The most common HTTP verbs are GET, POST, PUT, PATCH, and DELETE.

- What should the URIs be based on?

The URI should be based on the resource the API exposes. For example, if the API exposes a collection of books, the URI should be based on the book resource, such as /API/books.

- Give an example of a good URI.

A good URI is one that is easy to read and understand. It should be descriptive of the resource it identifies and follow a consistent naming convention.

- What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

A ‘chatty’ web API is one that requires multiple HTTP requests to perform a single operation. This is generally considered a bad thing as it can lead to performance issues and unnecessary network traffic.

- What status code does a successful GET request return?

A successful GET request returns a status code of 200 (OK).

- What status code does an unsuccessful GET request return?

An unsuccessful GET request returns a status code of 404 (Not Found).

- What status code does a successful POST request return?

A successful POST request returns a status code of 201 (Created).

- What status code does a successful DELETE request return?

A successful DELETE request returns a status code of 204 (No Content).

## Things I want to know more about
