💬 Real-Time Chat Application

A real-time chat application built using Spring Boot WebSocket and the STOMP protocol for instant and reliable messaging.

📌 About the Project

This project enables real-time communication between users using WebSockets with STOMP messaging and SockJS fallback for better browser compatibility.

🛠 Tech Stack

Spring Boot, Spring WebSocket, STOMP, Thymeleaf, JavaScript (ES6), SockJS, STOMP.js, HTML, CSS, Bootstrap, Maven
```
📂 Project Structure
├── src/                     # Application source code
│   ├── controller/          # WebSocket controllers
│   ├── config/              # WebSocket & STOMP configuration
│   ├── model/               # Message models
│   └── templates/           # Thymeleaf templates
├── .mvn/wrapper              # Maven wrapper
├── pom.xml                   # Maven dependencies
├── mvnw / mvnw.cmd           # Maven scripts
├── .gitignore
└── README.md
```
🚀 Features

.Real-time messaging using Spring Boot WebSocket

.STOMP protocol for message routing

.SockJS fallback for browser compatibility

.Responsive UI using Bootstrap

.Server-side rendering with Thymeleaf
```
▶️ How to Run
./mvnw spring-boot:run
```
```
Open in browser:

http://localhost:8080
```
📄 License

This project is for learning and demonstration purposes.
