# Real-time Chat Application

A simple real-time chat application built with **Spring Boot** on the backend using **WebSocket + STOMP** protocol and a Bootstrap-based frontend.  
Messages are pushed in real-time between connected users.

---

## Features

- Real-time messaging with WebSocket and STOMP
- Spring Boot backend with WebSocket support
- SockJS fallback for browsers without WebSocket support
- Simple Bootstrap UI for chat interface
- User can enter their name and send messages
- Messages broadcasted to all connected clients

---

## Tech Stack

- Java 17+ / Spring Boot
- Spring WebSocket + STOMP
- SockJS
- Bootstrap 5
- HTML, JavaScript (Vanilla)

---

## How to Run Locally

### Prerequisites

- Java 17 or higher installed
- Maven installed
- Git installed

### Steps

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/realtime-chat-app.git
   cd realtime-chat-app
