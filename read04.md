> # Data Modeling

> ## NoSQL vs SQL

&nbsp;

> 1. What type of database is the best fit for the complex query intensive environment?

SQL

> 2. What type of database is the best fit for hierarchical data storage?

NoSQL

> 3. Describe the differences in scalability between a SQL and NoSQL database as though you were speaking to a non-technical friend.

When it comes to scalability, you can think of it as quality vs quantity. To scale SQL, you generally want more quality -- more powerful servers. But to scale NoSQL, you generally want more quantity -- simply more servers than you currently have.

> ## SQL Modeling Techniques

&nbsp;

> 1. Among data tables, what is a one-to-many relationship and how do we “relate” them?

A one-to-many relationships is where an entry in one table can be related to more than one entry in a different table. Relationships are defined by matching a primary key with a foreign key.

> 2. Prior to designing your relational database, it might be useful to ______ of the database tables and their relationships.

create a diagram

> 3. Explain the difference between a primary and foreign key.

A primary key is used to uniquely identify each entry (row). The values in the primary key column are unique and are not repeated in that column. A foreign key may or may not uniquely identify entries, but a foreign key does match a primary key in a different table.

> ## SQL vs NoSQL

&nbsp;

> 1. How do we treat keywords and parameters differently in SQL syntax?

Keywords are generally typed/representated in all caps to distinguish them from parameters. 

> 2. Define normalization within the context of schemas and data.

All records (data) in a table follow the set schema (fill up the same number of columns). Normalization ensures that records which would otherwise have "extra" columns/data or "missing" columns/data actually fit the schema once they are added the table.

> 3. Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.

One-to-one: When one thing only pairs with one other thing. For example: your Social Security Number, a passport, or a voter registration.
One-to-many: You buy three things off of Amazon. Your Amazon account will be linked to those three purchases, and the purchases will only be associated with your account. Your Amazon account is the "one" and the three things you buy are the "many".
Many-to-many: User roles in a Facebook group: You might be an admin, a member, and other roles. And the same could be true of other people as well. One person could have many roles, and many people could have the same role. Many-to-many.
