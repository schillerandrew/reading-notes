> # Socket.io

> ### WebSocket

1. What is a Web Socket?

commnication protocol that has full-duplex channels (at-will commnication in either direction) or a single TCP connection

2. Describe the Web Socket request/response handshake and what happens once the connection is established.

The request/response handshake follows the standard pattern of the client sending an HTTP request and receiving a response from the server. Once the handshake is completed and the connection is established, communication moves from the HTTP protocol to full-duplex communication.

3. Web Sockets provide a standardized way for the server to send content to a client without first receiving a ____ from that client.

request

> ### Socket.io tutorial

1. What does the event handler io.on() do?

It connects event handling to event triggers.

2. Describe some possible proof of life or proof that the code works as expected.

Once events are correctly set up -- subscribed to and published -- a simple console log in the event handling is often an easy way to confirm proof of life or the event triggering and handling as expected.

3. What does socket.emit() do?

Sends a message (broadcasts) to connected clients.

> ### SOcket.io vs WebSocket

1. What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).

WebSocket is a communication protocol, and Socket.io is a library that "sits on top of" and uses the WebSocket protocol.

2. When would you use Socket.io?

If you need broadcasting, fallback, or proxies and load balancers.

3. When would you use WebSockets?

If you don't need the features of Socket.io. Compatibility with WebSockets is much more common now, and it requires fewer resources than Socket.io.

> ### OSI model explained

1. What are a couple of key takeaways from this video?

- Things which use an OSI layer don't reside at that layer, but they use protocols at that layer. Examples in the application layer are: FTP (file transfer), HTTP/S(Web browsing), SMTP (email), Telnet (virtual terminals).

- Some major transport layer protocols are:

  - Transmission Control Protocol (TCP) which is: connection-oriented transmission, slower (used with birectional) and allows for feedback
  - User Datagram Protocol (UDP) which is: connectionless transmission, faster (used with unidirectional) and doesn't allow for feedback

> ### TCP Handshakes Explained

1. Translate the gist of this video to a non-technical friend.

A three-way handshake allows for a client and server to first agree to establish a connection, and then for the connection to be established. By making it a three-way handshake instead of a two-way handshake, the server is first able to "verify" the client's request, and then the client is able to "verify" the server's response, before moving to step three which creates the connection that was agreed upon by both the client and server.
