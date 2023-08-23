## In your own words, describe what each group of status code represents:

- 100’s = Informational responses indicating that the server received and is processing the request.
- 200’s = Success responses indicating the request was successfully received, understood, and accepted.
- 300’s = Redirection responses telling the client the requested content has moved and needs further action.
- 400’s = Client error responses indicating the request contains bad syntax or cannot be fulfilled by the server.
- 500’s = Server error responses indicating the server failed to fulfill a valid request.

## What is a status code 202?

The request has been accepted for processing, but it has not completed yet.

## What is a status code 308?

The requested resource has been permanently moved to another location.

## What code would you use if an update didn’t return data to a client?

204 No Content

## What code would you use if a resource used to exist but no longer does?

410 Gone

## What is the ‘Forbidden’ status code?

403

## Why do we need to pull our MongoDB database string out of our server and put it into our .env?

To protect sensitive data and enable environment-specific configurations.

## What is middleware?

A software that acts as a bridge between an operating system or database and applications, providing functions beyond those offered by the OS.

## What does app.use(express.json()) do?

Parses incoming JSON payloads into JavaScript objects for Express apps.

## What does the `/:id` mean in a route?

`/:id` in a route captures variable values from the URL.

## What is the difference between `PUT` and `PATCH`?

`PUT` typically replaces an entire resource while `PATCH` updates parts of it.

## How do you make a default value in a schema?

In a schema, default values are set using the `default` property.

## What does a 500 error status code mean?

An internal server error.

## What is the difference between a status 200 and a status 201?

Status `200` means "OK," while `201` indicates a resource was successfully created.

## Resource Links

[Status Codes Based On REST Methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)

[Build A REST API With Node.js, Express, & MongoDB - Quick](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw)
