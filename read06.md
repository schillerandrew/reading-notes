> # Authentication

> ## Securing passwords


1. Explain to a non-technical friend how you would safely hash and store a password.

There are many options for hashing a password, and plaintext passwords are stored separately from hashed passwords.

2. What is Bcrypt?

An adaptive hash function that uses a work factor (or security factor) to control the speed of hash functions.

3. Why might you use something like Bcrypt?

It's useful against brute force attacks.

> ## Basic authentication

1. What is Basic Authentication?

A method for providing a username and password when making a request. It's the simplest way to enforce access controls to web resources because it uses fields in the HTTP header.

2. What properties are necessary in the header of a Basic Auth request?

username and password

3. How are username:password in Basic Auth encoded?

They're encoded with Base64, but since they aren't encrypted or hashed, BA is usually combined with HTTPS, to provide confidentiality for the credentials.

> ## [OWASP authentication cheatsheet](https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html)

1. Define the authentication process to a non-technical recruiter.

Authentication means verifying that a user, website, etc is who it claims to be -- "authentic". This is usually achieved by scrutinizing a username and password (or other private piece of information) submitted by the user.

2. How should your error messaging respond (both HTTP and HTML)? Why?

Responses should be generic, so that potential attackers can't use the responses to glean information about an account.

3. Bookmark this link also and consider OWASP fundamentals any time you interact with authentication. Applications developed with security in mind from inception have fewer vulnerabilities throughout their lifecycle.
