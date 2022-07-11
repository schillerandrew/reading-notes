> # AWS: Cloud Servers

> ## AWS EC2

> ### 1. What is an EC2 instance?

An EC2 instance is a virtual server on EC2. If you were providing your own on-site servers, you'd run things on those. When you use AWS, you run on a virtual server, an EC2 instance.

> ### 2. Name two use cases for EC2.

EC2 is secure, reliable, and cost-effective, even compared to in-house server solutions. In many cases, businesses prefer AWS over handling their own servers.

> ### 3. Provide one reason to use ECS instead of Heroku.

ECS can offer speed, reliability, and options that in some or many cases Heroku can't. A beefier app/service/project may need to reside on EC2.

> ## EC2 for Humans

> ### Where can we find EC2 on the AWS Console?

in the compute section

> ### Explain the general difference between T2 Micro and XL.

Both are in the same "family" (general purpose/burst category) but the XL offering provides more power -- more CPUs and RAM.

> ### Explain a “Compute Cycle” to a non-technical friend.

The compute cycle refers to a standard unit of computing -- computing power, computing time, etc. But although is more can be more standardized when it comes to physical (or non-virtual) CPUs and servers, cloud computing (AWS) is even harder to standardize. But the compute cycle is the general idea of how much bang for your buck are you getting -- not just in terms of money, but how efficient and/or powerful a given CPU or virtual server is.

> ## Elastic Beanstalk

> ### What is Elastic Beanstalk?

An AWS service that handles deployment and scaling of web applications

> ### Describe the relationship between EC2 and Elastic Beanstalk.

Both are AWS services. Elastic Beanstalk would run more or less "on top" of one or more EC2 instances, and be targeted at elastic cloud deployment. EC2 isn't always coupled with EB, it can be coupled with many other things besides or in addition to EB, and EC2's purpose is to provide cloud-based virtual servers.

> ### Name some benefits of using Elastic Beanstalk.

- It can deploy services built using major languages, such as Node.js, Java, Python and Ruby.
- It allows developers to focus on more on development and less on system administration.
