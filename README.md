

---

# Java Chatting Application

This is a simple Chatting Application built using Java Swing for the GUI and socket programming for the communication between the client and server. The application demonstrates basic concepts of networking in Java, such as socket connections, data input/output streams, and multithreading. 

## Features

- **Real-time Chat**: Clients can send and receive messages in real-time.
- **Typing Indicator**: Displays a "typing..." status when the other user is typing.
- **User Interface**: Simple and intuitive user interface using Java Swing.
- **Customization**: The UI is designed with a toolbar including buttons for exit, video call, and phone call (icons only, not functional).
- **Scrollable Chat**: Chat area is scrollable for easy navigation through past messages.

## Components

- **Server**: Manages the connection with clients and handles incoming and outgoing messages.
- **Client**: Allows users to send and receive messages to/from the server.

## Installation and Setup

### Prerequisites

- JDK 8 or above installed.
- A Java IDE (e.g., IntelliJ IDEA, Eclipse) or a simple text editor.
- Basic knowledge of Java and socket programming.

### Steps to Run

1. **Clone the Repository**
    `
    git clone https://github.com/Drak-Side/chat.git
    cd chat
    `

2. **Compile the Code**
    - Open the project in your preferred Java IDE or compile it manually using the command line.
    - If you're using the command line, navigate to the project directory and run:
      `
      javac -d bin src/chatting/application/*.java
      `

3. **Run the Server**
    - Run the `Server` class file:
      `
      java chatting.application.Server
      `

4. **Run the Client**
    - In another terminal or command prompt, run the `Client` class file:
      
      `java chatting.application.Client`
      

5. **Chat Away!**
    - The client window will open, and you can start chatting by typing a message and clicking the "Send" button.

## Code Structure

```
├── src
│   └── chatting
│       └── application
│           ├── Server.java
│           ├── Client.java
│           └── icons
│               ├── 1.png
│               ├── 2.png
│               ├── 3.png
│               ├── 3icon.png
│               ├── phone.png
│               └── video.png
└── README.md
```

- **Server.java**: Contains the server-side logic to handle incoming connections and message forwarding.
- **Client.java**: Contains the client-side logic for connecting to the server and sending/receiving messages.
- **icons**: Folder containing images used in the user interface.

## Customization

- **Icons**: The icons used in the toolbar can be replaced with custom images.
- **User Interface**: The UI components such as fonts, colors, and layout can be customized in the `Server.java` and `Client.java` files.

## Future Improvements

- **Multithreading**: Improve the server to handle multiple clients simultaneously using multithreading.
- **Database Integration**: Store chat history in a database for future retrieval.
- **Enhanced Features**: Add functionalities like file sharing, group chat, and notifications.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Inspired by simple chat applications built with Java.
- Java Swing for the user interface components.
- Various online resources for understanding Java socket programming.

---
