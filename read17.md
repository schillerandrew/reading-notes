> # AWS: S3 and Lambda

> ## AWS S3

> ### 1. What is Amazon S3?

Amazon Simple Storage Service (S3) is an AWS service that provides persistent data storage to back-end anything you want.

> ### 2. Name some use cases for Amazon S3.

The use cases for Amazon S3 are extremely open-ended. If you need to host something in the cloud or on AWS, and it needs storage, you will probably hook up to S3 for storage needs.

> ### 3. Name some benefits of using Amazon S3.

S3 touts all of the usual features for a storage solution: availability (99.99%), security, and flexibility. As part of the AWS suite, it's easy to combine S3 with other services. Also, because AWS is such a popular cloud solution, S3 probably tends to be one of the cheapest options.

> ## AWS Lambda Basics

> ### 1. What is AWS Lambda?

Lambda is a serverless computing service that focuses on the creation of individual programming functions. Lambda handles all of the back-end infrastructure, such as servers, so that the user can focus on code -- similar to Elastic Beanstalk, but Lambda seems to be even more laser-focused and maybe caters to smaller apps or functions.

> ### 2. Name some use cases for AWS Lambda.

Lambda seems to be a little particular about its use cases: It's better for things that run quickly,  that are usually self-contained, or that have very low workloads or very high workloads.

> ### 3. Describe “serverless” to a non-technical friend.

Serverless is slightly misleading. All major computing has to use servers to request and receive data. Serverless doesn't mean that servers aren't involved, it just means that the management of the servers is handled by someone else. Whatever you're working on, you can focus more on that and less on maintaining the servers.

> ## CDN

> ### 1. What is a CDN?

A content delivery network is a group of servers that is spread out geographically to provide fast delivery of Web content.

> ### 2. How does a CDN work with relation to the website visitor?

When someone visits a website, the CDN server that is nearest to them will "serve" the website data to them. Website data is cached so that if requests repeatedly come in, that CDN server may already have the data that the user needs. And if the nearest CDN server doesn't already have all of the necessary data, it gets it from the CDN and caches it and provides it to the user.

> ### 3. What are the benefits of employing a CDN?

CDNs improve the speed of website loading and also content delivery -- which can be a big deal when it comes to attracting and keeping users/customers. CDNs can also protect against distrubuted denial-of-service (DDos) attacks, because CDNs already have their data and resources geographically distributed and are readily able to shift that distribution -- a kind of redundancy.
