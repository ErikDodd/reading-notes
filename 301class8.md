# Code 301 - Class 8 - Reading Notes

## API Design Best Practices

**1. What does REST stand for?**

- Representational State Transfer

**2. REST APIs are designed around a ____.**

- resources (any kind of object, data, or service that can be accessed by the client)

**3. What is an identifier of a resource? Give an example.**

- A URL that uniquely identifies a particular resource.
- <https://adventure-works.com/orders/1>

**4. What are the most common HTTP verbs?**

- GET, POST, PUT, PATCH, DELETE

**5. What should the URIs be based on?**

- Nouns (the resource)

**6. Give an example of a good URI.**

- <https://adventure-works.com/orders>

**7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?**

- A chatty web API is a web request that does multiple things and has a bigger load to impose on the web server. It is a bad thing because it can cause extra bandwidth costs.

**8. What status code does a successful GET request return?**

- 200 (OK)

**9. What status code does an unsuccessful GET request return?**

- 404 (Not found)

**10. What status code does a successful POST request return?**

- 201 (Created)

**11. What status code does a successful DELETE request return?**

- 204 (No Content)

References:

1. [RESTful web API design](https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design)
