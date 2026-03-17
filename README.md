# Network Calculator (TCP Client-Server)

A C-based networking application that performs arithmetic operations using the TCP/IP protocol. This project demonstrates basic socket programming and client-server architecture in a Linux environment.

## Features
* **TCP Sockets:** Reliable communication between client and server.
* **Expression Parsing:** Server-side logic to parse strings and calculate results (+, -, *, /).
* **Error Handling:** Robust checks for socket creation, binding, and connection.
* **Clean Code:** Extensively commented source code for better readability and maintenance.

## How it Works
1. The **Server** starts and listens on a specific port.
2. The **Client** connects to the server and sends a mathematical expression (e.g., "10 + 5").
3. The **Server** processes the request, calculates the result, and sends it back.
4. The **Client** displays the result and closes the connection.

## Technologies Used
* C Language
* POSIX Sockets API
* Linux Systems Programming
