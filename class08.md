> # APIs

1. What does REST stand for?

    -Representational State Transfer
1. REST APIs are designed around a ____.

    -uniform interface
1. What is an identifier of a resource? Give an example.

    -a URI that uniquely identifies the resource -- ex: HTTP -> `https://adventure-works.com/orders/1`
1. What are the most common HTTP verbs?

    -`GET`, `POST`, `PUT`, `PATCH`, `DELETE`
1. What should the URIs be based on?

    -resources
1. Give an example of a good URI.

    -`https://adventure-works.com/orders` (HTTP)
1. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

    -the potential to require a large number of small resources; it's a balance of good and bad-- larger chunks of data may cut down on 'chattiness' but may also lead to providing extra data that the requester doesn't need
1. What status code does a successful GET request return?

    -200 (OK)
1. What status code does an unsuccessful GET request return?

    -404 (not found)
1. What status code does a successful POST request return?

    -201 (created)
1. What status code does a successful DELETE request return?

    -204 (no content)
    