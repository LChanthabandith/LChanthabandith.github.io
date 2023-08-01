## What does REST stand for?

Representational State Transfer

[API Design Best Practices](https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design)

## REST APIs are designed around a ____.

REST APIs are designed around *resources*, which are any kind of object, data, or service that can be accessed by the client.

[API Design Best Practices](https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design)

## What is an identifier of a resource? Give an example.

A resource has an identifier, which is a URI that uniquely identifies that resource. For example, the URI for a particular customer order might be:

```
https://adventure-works.com/orders/1
```

[API Design Best Practices](https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design)

## What are the most common HTTP verbs?

The most common operations are GET, POST, PUT, PATCH, and DELETE.

[API Design Best Practices](https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design)

## What should the URIs be based on?

When possible, resource URIs should be based on nouns (the resource) and not verbs (the operations on the resource).

[API Design Best Practices](https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design)

## Give an example of a good URI.

```
https://adventure-works.com/orders // Good
```

[API Design Best Practices](https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design)

## What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

The more requests, the bigger the load. Try to avoid "chatty" web APIs that expose a large number of small resources.

[API Design Best Practices](https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design)

## What status code does a successful `GET` request return?

A successful `GET` method typically returns HTTP status code 200 (OK).

[API Design Best Practices](https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design)

## What status code does an unsuccessful `GET` request return?

If the resource cannot be found, the method should return 404 (Not Found).

[API Design Best Practices](https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design)

## What status code does a successful `POST` request return?

If a POST method creates a new resource, it returns HTTP status code 201 (Created).

[API Design Best Practices](https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design)

## What status code does a successful `DELETE` request return?

If the `delete` operation is successful, the web server should respond with HTTP status code 204 (No Content), indicating that the process has been successfully handled, but that the response body contains no further information.

[API Design Best Practices](https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design)
