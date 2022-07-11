> # AWS: Events

> ## AWS SQS vs SNS

> ### 1. What is the difference betweeen SQS and SNS?

With SNS, messages are pushed to recipients, and with SQS, recipients pull their messages.

> ### 2. What are some use cases for both SNS and SQS?

SNS:

- Publishing batches of messages
- Messages are processed in different ways
- Multiple subscribers

SQS:

- Simple queue
- One subscriber
- Asynchronous message delivery

> ## AWS SNS and SQS

> ### 1. Describe how to use SQS and SNS in a “fanout” pattern.

In the fanout pattern, an SNS publishes to an SQS, which then queues messages. The SQS is a recipient of the SNS, and the SQS has its own recipients, who it reaches with its queue method.

> ### 2. Explain how “push notifications” work, using SNS.

Push notifications are a great example of SNS. I routinely receive them from Facebook notifying me that one or more of my Facebook friends have an upcoming birthday. That message probably goes out to a lot of that person's Facebook friends -- depending on your settings. I didn't specifically request that message, but I received it, along with a lot of other people, and then we handle that message in different ways.

> ## SQS and SNS Basics

> ### 1. How might a large scale, distributed application make use of a Queue system like SQS?

Queueing can allow for more steady handling of tasks. In a large-scale application, you can imagine large demands on certain parts of the app at certain times. With queueing, and effective polling of queues, the queue is less likely to overwhelm the services that clear things out of that queue, because the queue doesn't assign its tasks and doesn't assign them en masse. Instead, the service pulls from the queue when it's ready to.