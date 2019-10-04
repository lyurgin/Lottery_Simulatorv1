# Networking Examples using JAVA

# Simple Server - Client
This example shows how to establish a connection between client and server using ***ServerSocket*** and ***Socket*** objects in Java. 

- The server listen for connections and once it accepts one a string is returned and the connection is closed. 

- The client connects to the server, reads the server response and terminates.

# Echo Server - Client
This example shows how extends the SimpleServer to work as a traditional ***echo*** server. 

- The server listen for connections and once it accepts, keeps reading the client socket. For each string received, added some formatting and write it back to the client.
- The client connects to the server, reads STDIN for a string. Sends that string to the server and waits for the server response.