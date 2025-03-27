# Java Chatting Application

## Overview
This is a simple chatting application built in Java using Socket programming. It allows real-time messaging between a server and a client using a graphical user interface (GUI) built with Swing.

## Features
- One-to-one real-time chat
- Graphical User Interface (GUI) using Java Swing
- Server-client communication over sockets
- Message timestamping
- Active status display

## Technologies Used
- **Programming Language:** Java
- **GUI Library:** Swing
- **Networking:** Java Sockets (ServerSocket, Socket)

## How It Works
The application consists of two main components:
1. **Server**: Listens for incoming client connections and relays messages.
2. **Client**: Connects to the server and enables sending and receiving messages.

## Setup Instructions
### Prerequisites
- Java Development Kit (JDK) installed
- Any Java IDE (e.g., IntelliJ IDEA, Eclipse, NetBeans) or a simple text editor

### Running the Application
#### Step 1: Start the Server
1. Open the `Server.java` file.
2. Compile and run the server using:
   ```sh
   javac Server.java
   java Server
   ```

#### Step 2: Start the Client
1. Open the `Client.java` file.
2. Compile and run the client using:
   ```sh
   javac Client.java
   java Client
   ```
3. The client will establish a connection to the server.
4. Start chatting!

## Screenshots
_Add screenshots of the chat application here._

## Future Enhancements
- Support for multiple clients (group chat feature)
- Database integration for message history
- User authentication and login system
- File sharing feature

## Contributors
Ujjawal kumar verma - Developer



