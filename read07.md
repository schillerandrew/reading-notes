> # Bearer Authorization

> ### Intro to JWT

1. What is a JSON Web Token (JWT)?

a standard way for secururely transmitting JSON objects

1. When should we use JSON Web Tokens?

authorization (most common)/Single Sign On, information exchange

1. Claims are expected in which structural component of a JWT?

payload

> ### Are JWTs Secure?

1. If I get a JWT and I can decode the payload, how can we call that secure?

Changing the payload changes the signature, and the recipient will be able to tell that the signature doesn't match, and thus that the payload was changed.

1. If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.

the secret

1. Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.

Encryption is one way to securely send data. Even without encryption, the use of JSON Web Tokens (known as JWTs) and signatures allows data recipients to be sure that data is authentic. If data is changed, then the signature also changes (or the signature is no longer what you expect it to be) and that's how the receipient knows the data was changed.

> ### JWTs Explained

1. Why use JWT?

authentication and information exchange

1. JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.

Because JWT is compact and self-contained, it's very fast, and that's a big deal in software, especially when it comes to data transmission.

1. What are the three components (the structure) of a JWT signature?

an encoded header, an encoded payload, and a secret
