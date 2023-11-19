## **Java Chat Application**
This is a simple command-line-based chat application implemented in Java using ServerSocket and Socket for communication between a server and a client.

**Overview**
: The chat application consists of two main components: the server and the client. The server waits for incoming connections, and once a connection is established, it allows for real-time communication between the server and the client.

**Features**
: Real-Time Chat: The server and client can send and receive messages in real-time.
Exit Command: Users can terminate the chat by entering "exit" as a message.

**How to Run**
: 1. Server
Run the Server.java file.
The server will start and wait for incoming connections on port 7777.<br>
2. Client
Run the Client.java file.
The client will attempt to connect to the server at 127.0.0.1 (localhost) on port 7777.
Once the connection is established, the user can start sending and receiving messages.

**How to Run**
: Type your messages in the console to send them to the connected user.
Enter "exit" to close the chat connection.

**Dependencies**
: The application has no external dependencies and uses the standard Java Socket and BufferedReader classes for communication.
