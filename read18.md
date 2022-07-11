> # AWS: API, Dynamo and Lambda

> ## AWS API Gateway Overview

> ### 1. What is Amazon API Gateway?

An AWS service that lets you define HTTP endpoints of a REST API or WebSocket API and connect the endpoints.

> ### 2. Why is Amazon API Gateway an important part of the Serverless ecosystem?

It ties together all of the serverless services and APIs.

> ### 3. How does API Gateway integrate with other AWS services?

It has built-in compatibility with many AWS services, including Lambda, SNS and Amazon Cognito.

 > ## AWS API Gateway

> ### 1. What are the some benefits of using Amazon API Gateway?

All of the usual benefits -- scalability, security, cost savings -- and a great way to host an API, even multiple versions of the same API, or different kinds of APIs: REST, HTTP and Websocket.

> ### 2. What two API types might you choose from?

RESTful and WebSocket

> ## AWS DynamoDB Guide

> ### 1. What is DynamoDB?

Amazon's NoSQL database service offering

> ### 2. Under what circumstances would you recommend DynamoDB over MongoDB?

- If managing the database is going to be a pain point -- DynamoDB offers as many instances and as much scaling up or down as you need
- If you're using "hyper-ephemeral" computing like AWS Lambda where you spin up and spin down instances much more quickly and frequently

> ## AWS DynamoDB

> ### 1. Explain to a non-technical friend how DynamoDB works.

Amazon Web Services provides all kinds of services that websites need, and DynamoDB is their service that provides a NoSQL database in the cloud. DynamoDB, like other AWS services, lets you run as many databases -- they're called instances -- as you want, and DynamoDB is good at being very flexible but consistent. You can expand your databases and have more of them, or shrink them down, and DynamoDB handles a lot of the behind-the-scenes changes that you'd normally handle with growing or shrinking your database footprint.

> ## Dynamoose

> ### 1. What is Dynamoose?

Dynamoose handles models for DynamoDB -- similar to Mongoose with MongoDB.

> ### 2. What are some key features of Dynamoose?

- User-friendly syntax
- Strict data modeling
- Callback and promise support