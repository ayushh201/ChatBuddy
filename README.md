# ChatBuddy

ChatBuddy is a mini WhatsApp type chat model that allows users to create, edit, update, and delete chats. This project is built using Node.js, Express.js, REST API, MongoDB, HTML, CSS, and JavaScript.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)


## Features

- Create new chat messages.
- Edit existing chat messages.
- Update chat messages.
- Delete chat messages.
- User authentication and authorization.
- Real-time chat updates using WebSockets.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/ChatBuddy.git
    ```

2. Navigate to the project directory:
    ```bash
    cd ChatBuddy
    ```

3. Install the dependencies:
    ```bash
    npm install
    ```

4. Set up the environment variables:
    Create a `.env` file in the root directory and add the following variables:
    ```env
    PORT=8080
    MONGODB_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    ```

5. Start the server:
    ```bash
    npm start
    ```

## Usage

1. Open your browser and navigate to `http://localhost:8080`.
2. Register a new account or log in with existing credentials.
3. Start creating, editing, updating, and deleting chat messages.

## API Endpoints

- **POST /api/auth/register**: Register a new user.
  
- **POST /api/auth/login**: Log in an existing user.
  
- **GET /api/chats**: Get all chat messages.
  
- **POST /api/chats**: Create a new chat message.
  
- **PUT /api/chats/:id**: Update a chat message.

- **DELETE /api/chats/:id**: Delete a chat message.

## Technologies Used

- **Node.js**: JavaScript runtime environment.
- **Express.js**: Web framework for Node.js.
- **MongoDB**: NoSQL database.
- **Mongoose**: MongoDB object modeling tool.
- **HTML/CSS**: Frontend structure and styling.
- **JavaScript**: Programming language for frontend interactivity.
- **WebSockets**: For real-time communication.

## Contributing

We welcome contributions to enhance the project! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature/your-feature-name
    ```
3. Commit your changes:
    ```bash
    git commit -m 'Add some feature'
    ```
4. Push to the branch:
    ```bash
    git push origin feature/your-feature-name
    ```
5. Create a pull request.

Thank you for using ChatBuddy! If you have any questions, feel free to open an issue on GitHub.
