> # `<Login />` and `<Auth />`

> ## What is Role Based Access Control (RBAC)?

> ### 1.  What is Role Based Access Control (RBAC)?

Controlling access based on a role, rather than directly assigning privileges. The role is used as an intermediary between users and user rights.

> ### 2.  Share some an example of RBAC including all possible CRUD operations and correlating roles.

For example, controlling just CRUD access:

- user: READ
- writer: CREATE, READ
- editor: CREATE, READ, UPDATE
- admin: CREATE, READ, UPDATE, DELETE

> ### 3.  What are the Benefits of RBAC?

- Modularized access -- Add or remove roles quickly and easily
- Organized and modeled -- Roles are aligned with business needs/organization, so access control is more intuitive and more consistent.
- Resilient and compliant -- A more modeled but also modularized access control system makes it easier to mesh with regulations or compliance.

> ## react-cookie library and react-cookies component

> ### 1.  Describe some react-cookie features.

- `get` and `getAll` method
- `set` method
- `remove` method
- `withCookies` can provide access to cookies anywhere
- `useCookies` allows React Hooks to access and modify cookies

> ### 2.  Describe some react-cookies features.

- `plugToRequest` and `setRawCookie` methods allow you to access cookies while doing server rendering
- `load` (get) and `loadAll` (getAll) methods
- `save` (set) method
- `remove` method

> ### 3.  Which library would you prefer? Why?

react-cookies explicitly says it's a modified version of react-cookie 1.0.4. But both seem to be pretty similar and perhaps have server-rendering features. I'd probably use react-cookie because it's much more recent and also seems to be more widely used -- although not as much as universal-cookie.
