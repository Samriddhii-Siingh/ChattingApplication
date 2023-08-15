# Chatting Application

The Chatting Application in Java is a simple yet effective program that enables real-time communication between clients and a central server. This project showcases the implementation of a chat interface where users can exchange messages seamlessly.

## Features

- **Real-Time Messaging:** Engage in instant conversations with other users connected to the server.
- **Graphical User Interface:** Both the client and server come with user-friendly GUIs, making interaction intuitive.
- **Timestamps:** Each message is timestamped for easy tracking of the conversation.
- **Message Formatting:** Messages are formatted for improved readability and clarity.
- **Active Status Indicator:** The application displays the active status of users.
- **Effortless Communication:** Send and receive messages with just a few clicks.

## Getting Started

Follow these steps to set up and run the Java Chatting Application:

### Server

1. Compile and run the `Server.java` file on the designated server machine.
2. The server GUI will open, showing the online status of users.
3. The server starts listening for incoming connections on the specified port.

### Client

1. Compile and run the `Client.java` file on the client machine(s).
2. The client GUI will appear, providing a straightforward platform to exchange messages.
3. Type your message in the input field and click "Send" to dispatch messages.
4. Received messages, along with timestamps, will populate the message display area.

## Screenshots

### Server GUI
![Server GUI](/screenshots/server.png)

### Client GUI
![Client GUI](/screenshots/client.png)

## How It Works

1. The `Server` class creates a server socket to accept incoming connections.
2. Upon a client's connection, a dedicated socket is established for communication.
3. The `Client` class connects to the server using its IP address and port.
4. Messages between clients and the server are exchanged using input and output streams.
5. Messages follow a simple format, including sender's name, content, and timestamp.
6. The `formatLabel` function refines messages for display in the GUI.
7. The application continuously monitors incoming messages and updates the GUI in real time.

## Contributions

Contributions are welcome to enhance the application's features, refine the user interface, or address issues. If you're interested, fork the repository and submit pull requests.

## License

The project is licensed under the MIT License, granting you the freedom to use, modify, and distribute the code according to the license terms.
