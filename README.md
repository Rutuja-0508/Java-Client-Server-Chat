# Java Client-Server Chat Application

## About the Project

This project demonstrates client-server communication using Java Socket Programming and TCP/IP.

The application allows a client to send messages to a server, and the server can respond through a terminal-based interface.

The repository contains two implementations of the client-server chat application: an original version and a modified version with additional connection-termination handling.

## Technologies Used

* Java
* Java Socket Programming
* TCP/IP
* `Socket` and `ServerSocket`
* `BufferedReader` and `PrintStream`

## Project Structure

```text
Java-Client-Server-Chat/
├── Chat_Client.java
├── Chat_Server.java
├── Chat_ClientX.java
├── Chat_ServerX.java
├── README.md
└── .gitignore
```

## Implementations

### 1. Original Implementation

Files:

* `Chat_Client.java`
* `Chat_Server.java`

Features:

* Establishes a TCP connection between the client and server.
* Exchanges messages through terminal input and output.
* Uses port 5100 for communication.
* Demonstrates basic socket programming in Java.

### 2. Modified Implementation

Files:

* `Chat_ClientX.java`
* `Chat_ServerX.java`

Features:

* Includes additional checks for chat termination.
* Handles certain connection-closure scenarios.
* Displays messages when the client or server ends the conversation.

Note: The modified version improves connection-termination handling, but it is still a basic, turn-based chat application.

## Prerequisites

* Java Development Kit (JDK).
* A terminal or command prompt.
* Basic knowledge of Java.

## How to Run

### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/Java-Client-Server-Chat.git
```

Replace `YOUR-USERNAME` with your GitHub username.

### Step 2: Open the Project Folder

```bash
cd Java-Client-Server-Chat
```

### Step 3: Compile the Java Files

```bash
javac Chat_Client.java Chat_Server.java Chat_ClientX.java Chat_ServerX.java
```

### Step 4: Start the Server

Open a terminal and run one server implementation.

For the original version:

```bash
java Chat_Server
```

For the modified version:

```bash
java Chat_ServerX
```

### Step 5: Start the Corresponding Client

Open a second terminal in the same directory.

For the original version:

```bash
java Chat_Client
```

For the modified version:

```bash
java Chat_ClientX
```

Important: Run only one server and its corresponding client at a time because both server implementations use port 5100.

## Learning Outcomes

* Understanding client-server architecture.
* Establishing TCP connections using Java sockets.
* Sending and receiving messages through streams.
* Understanding basic network communication.
* Learning about connection termination and exception handling.

## Future Improvements

* Support multiple clients.
* Enable simultaneous two-way messaging.
* Add a graphical user interface.
* Implement user authentication.
* Improve connection and error handling.

## Author

Rutuja Patil
