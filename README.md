
A Real-Time Chat Application built using Spring Boot for the backend and WebSockets for real-time communication. The frontend is built with HTML, CSS, and JavaScript to provide a simple and responsive user interface.

--> Features
1)Real-time messaging using WebSocket protocol
2)Simple and responsive web-based chat UI
3)Broadcasts messages to all connected clients

Lightweight and easy to deploy

--> Tech Stack
Backend: Spring Boot, WebSocket, STOMP

Frontend: HTML, CSS, JavaScript

Build Tool: Maven or Gradle

Protocol: WebSocket with STOMP messaging

-> Project Structure
chat-application/
│
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com.example.chat/
│   │   │       ├── ChatApplication.java
│   │   │       ├── config/WebSocketConfig.java
│   │   │       ├── controller/ChatController.java
│   │   │       └── model/ChatMessage.java
│   │   └── resources/
│   │       ├── static/
│   │       │   ├── index.html
│   │       │   ├── style.css
│   │       │   └── app.js
│   │       └── application.properties
├── pom.xml
└── README.md
 -> Getting Started
Prerequisites
Java 17
Maven or Gradle
(VSCode)
