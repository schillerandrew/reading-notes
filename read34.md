> # API Integration

> ## Review API Server Build

> ### 1.  Explain the different between a query string parameter and a path parameter.

Path parameters are more so used to identify specific data, while query string parameters are then used to customize that data -- for example, sorting or filtering the data.

> ### 2.  What would our API URL with a path id parameter be given the following information:
  - Domain: http://our-site.com
  - v3
  - model name: stuff
  - id: things

  `http://our-site.com/api/v3/stuff/things`


> ### 3.  We have created a dynamic API with an “interface”. Describe how that interface works to a non-technical friend.

The interface is an attempt to be able to handle different kinds of inputs. An large online store would have all kinds of products, and all kinds of categories so customers can search and shop and find those products. So the store would need to manage and display those products and categories. An interface would in some ways merge together product handling and category handling -- and other things or areas as well -- so that hopefully any "thing" or any "data" which needs to be managed could be managed by the existing interface, with as few changes as possible.

> ## Review Auth Server Build

> ### 1.  Describe how you would use middleware to implement basic and bearer auth.

Basic and bearer auth can easily be handled by tying them to authentication, and sometimes authorization as well. Basic auth can use npm packages such as base64 and bcrypt to authenticate user credentials at login, and after that bearer auth can authorize different functionalities, using JWTs with the jsonwebtoken package.

> ### 2.  Describe the handshake necessary to implement OAuth.

1. register app with Google
2. user wants to log in
3. app lets user choose OAuth (Google) sign-in
4. Google sends a code and state variable
5. app checks state
6. app POSTs code to Google
7. Google sends app a token
8. token can be used to authorize the user

> ### 3.  Describe how Role Based Access Control works to a non-technical friend.

RBAC doesn't add or remove individual permissions to a user, it adds or removes many at once. And the permissions are bundled together according to a user's role. RBAC takes a little more upfront planning and implementation, but it makes it easier to manage access to resources. Instead of everyone having a mess of permissions, permissions are broken down by role, people with similar job responsibilites are given similar roles, and the system is easier to handle.
