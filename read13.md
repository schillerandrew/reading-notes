> # Message Queues

> ## Socket.io chat example

> ### 1. Explain to a non-technical recruiter what the Chat Example (above) does.

It creates a very, very simple chat application that allows users to send chat messages to everyone. With Socket.io it's helpful to think of two things: listening for an event, and triggering that event. In the chat app, when someone wants to "send" a chat message, the message event is triggered, and everyone else is automatically listening for that event, so they receive the message.

> ### 2. What proof of life are we getting on the backend from the above app?

Console log messages -- in this case, indicating that users connected and disconnected.

> ### 3. Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?

broadcast

> ## Rooms

> ### 1. What is a room and how might a room be useful?

A channel that sockets can join and leave. It's used to delineate between who can listen for an event and who can't.

> ### 2. How do you join a room?

`join` method

> ### 3. How do you leave a room?

`leave` method

> ## Namespaces

> ### 1. What is a namespace and what does it allow you to do?

A namespace is a communication channel that allows you to further separate server logic (and even client logic).

> ### 2. Each namespace potentially has its own what? (hint: 3 things)

event handlers, rooms and middlewares

> ### 3. Discuss a possible use case for separate namespaces.

One common use is creating an admin area that is separate from a user area.