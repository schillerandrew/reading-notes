> # Access Control (ACL)

> ### 5 Steps to RBAC

1. What is Role Based Access Control (RBAC) and why do we care?

Controlling system access to users according to their role and responsibilites within an organization. It's a common way of managing access with some advantages such as being systematic, repeatable, and easy to secure.

2. Describe a Role/Permission heirarchy that you might implement using RBAC.

customers > User > read/write
employees > Super User - read/write/update
IT/dev/op > Admin - read/write/update/delete

3. What approach might you take to implement RBAC?

- Inventory systems, to figure what access you are controlling
- Analyze your workforce, to create roles
- Assign people to roles
- Avoid one-offs (systemitize)
- Review/audit your RBAC system

> ### [RBAC Wiki](https://en.wikipedia.org/wiki/Role-based_access_control)

1. If Authentication is “you are who you say you are,” what is Authorization?

Authorization involves control what users have access to.

2. Name three primary rules defined for RBAC.

- Role assignment
- Role authorization
- Permission authorization

3. Describe RBAC to a non-technical friend.

RBAC is a system of roles and permissions that controls what users can do. There are many ways of implementing it, but it centers around assigning users to roles, which in turn can do certain things. Users aren't directly permissioned, the roles always connect users to their permissions, and in this way you can create a systemic approach that is easier to change and maintain. When you log into a website or buy something online, often you only have access to do certain things within your account. But an admin or someone who maintains the website would have access to do much more, with your account or with other accounts -- that's a potential example of RBAC.

> ### RBAC tutorial

1. What are access rights associated with? The user? or the role? Explain.

The role. Rights aren't directly connect to roles, so that there is a systemic and modular approach to permissioning. Even if a user needs to have specific rights that aren't covered by a current role, you might be able to assign multiple roles to accomodate, or create a new role.

2. Access rights, or authorization, is activated after a user successfully does what?

authenticates

3. Explain how RBAC might benefit a business.

Access control policies don't need to be updated when someone joins or leaves a business. Access to any kind of resources or information can be controlled for any and all employees.