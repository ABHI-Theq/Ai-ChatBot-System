

# AI Chatbot System

An AI-driven chatbot system designed to provide interactive and automated responses for user queries. This project uses a frontend built with HTML, CSS, and JavaScript, and a backend powered by Node.js integrated with a Java Spring Boot API, alongside MongoDB for data storage and JWT for authentication.

## Table of Contents
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Setup](#setup)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [API Endpoints](#api-endpoints)
- [License](#license)

---

## Features

- **Interactive Chatbot:** AI-driven responses to user queries, providing a seamless conversational experience.
- **Frontend:** Built with HTML, CSS, and JavaScript, offering a responsive and user-friendly interface.
- **Backend Integration:** Node.js server coordinating with a Java Spring Boot API to manage core functionality.
- **Database:** MongoDB for efficient data management.
- **JWT Authentication:** Protects API routes with secure access management.

## Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Node.js, Java Spring Boot
- **Database:** MongoDB
- **Authentication:** JSON Web Tokens (JWT)

## Setup

### Prerequisites
Ensure you have the following installed:
- [Node.js](https://nodejs.org/)
- [Java JDK](https://www.oracle.com/java/technologies/javase-downloads.html)
- [MongoDB](https://www.mongodb.com/)
- [Maven](https://maven.apache.org/)

### Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/AI-Chatbot-System.git
   cd AI-Chatbot-System
   ```

2. **Backend Setup**
   - Navigate to the `backend` folder and install Node.js dependencies:
     ```bash
     cd backend
     npm install
     ```
   - Build and run the Java Spring Boot API (ensure you have Maven configured):
     ```bash
     cd springboot-api
     mvn clean install
     mvn spring-boot:run
     ```

3. **Frontend Setup**
   - Open `frontend/index.html` in your preferred browser or use a local server to run the HTML file.

4. **MongoDB Setup**
   - Start the MongoDB server.
   - Configure the MongoDB connection URI in the `backend` configuration file.

5. **Environment Variables**
   - Configure your environment variables for MongoDB URI and JWT secrets.

## Usage

1. **Start the Node.js Backend**
   ```bash
   node app.js
   ```

2. **Access the Frontend**
   - Open `index.html` in a browser to access the chatbot interface.

3. **Testing the Chatbot**
   - Interact with the chatbot interface, which communicates with the backend to fetch and return responses.

## Project Structure

```
AI-Chatbot-System/
│
├── frontend/                   # Frontend code (HTML, CSS, JavaScript)
├── backend/
│   ├── node-app/               # Node.js server files
│   └── springboot-api/         # Java Spring Boot API code
└── README.md
```

## API Endpoints

Here are some key endpoints provided by the Java Spring Boot API (accessible via Node.js backend):

- **/api/auth/login** - Authenticate users and issue JWT.
- **/api/chat/respond** - Handle chat responses from the AI.
- **/api/data** - Manage data retrieval and storage in MongoDB.

## License

This project is not licensed yet.

---

Feel free to customize further as per your project's specific structure or requirements.
