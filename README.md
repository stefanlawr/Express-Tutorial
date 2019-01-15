# Express-Tutorial

I will be [this video](https://www.youtube.com/watch?v=pKd0Rpw7O48) tutorial for building a RESTful API with Node and Express.

# What is a RESTful API?

Client / Server architecure using HTTP protocol. Server exposes a bunch of services accessible via HTTP protocol. The client can then directly call these services via HTTP requests.

**R**epresentational **S**tate **T**ransfer

REST is a convention for building these HTTP services.

We use simple HTTP protocol principles to provide support to Create, Read, Update, and Delete data. These are CRUD operations.

# Real World Example

We have a company, Test, with a client app where we manage the list of our customers. On the server, we should expose a service with an endpoint such as:

`http://test.com/api/customers`

The address can be reached at http or https.

We then have the companies domain.

We have `/api/` as a convention to expose our RESTful services.

We then have `/customers` which refers to the collection of customers in our applications. This is refered to as a `resource`.
This is our endpoint to work with the customers. All HTTP requests to manipulate the customer should be sent to this endpoint.

# HTTP Methods

**GET** for getting data.  
**POST** for creating data.  
**PUT** for updating data.  
**DELETE** for deleting data.
