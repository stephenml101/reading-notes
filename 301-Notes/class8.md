# Things I want to know more about:


[API Design Best Practices](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)

1. What does REST stand for?

- Representational State Transfer

2. REST APIs are designed around a ____.

- REST APIs are designed around resources, which are any kind of object, data, or service that can be accessed by the client.

3. What is an identifier of a resource? Give an example.

- A URI that uniquely identifies that resource. [https://adventure-works.com/orders/1](https://adventure-works.com/orders/1)
- {"orderId":1,"orderValue":99.90,"productId":1,"quantity":1}

4. What are the most common HTTP verbs?

- GET, POST, PUT, PATCH, and DELETE

5. What should the URIs be based on?

- nouns (the resource) and not verbs (the operations on the resource).

6. Give an example of a good URI.

- A resource doesn't have to be based on a single physical data item. For example, an order resource might be implemented internally as several tables in a relational database, but presented to the client as a single entity.

- [https://adventure-works.com/orders](https://adventure-works.com/orders)


7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

- All web requests impose a load on the web server. The more requests, the bigger the load.

8. What status code does a successful GET request return?

- Status code 200.

9. What status code does an unsuccessful GET request return?

- Status code 404.

10. What status code does a successful POST request return?

- Satus code 201.

11. What status code does a successful DELETE request return?

- Status code 204.

[RegExr](https://regexr.com/) - Pay particular attention to the cheatsheet

[Regex Tutorial](https://medium.com/factory-mind/regex-tutorial-a-simple-cheatsheet-by-examples-649dc1c3f285)

[Regex 101](https://regex101.com/)
