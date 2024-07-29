# Chat App using Socket.IO and Node.js

## Overview

This project is a real-time chat application built using Node.js and Socket.IO. It allows multiple users to join the chat, send messages, and see messages from other users in real-time. The front-end is styled using Tailwind CSS.

## Features

- **Real-time Communication:** Messages are sent and received in real-time using WebSockets.
- **User-Friendly Interface:** The UI is simple and intuitive, styled with Tailwind CSS.
- **Responsive Design:** The application works well on both desktop and mobile devices.
- **Message Broadcasting:** Messages from users are broadcasted to all connected clients.
- **Username Display:** Each message is prefixed with the username of the sender for easy identification.

## Getting Started

### Prerequisites

- Node.js (v12 or later)
- npm (v6 or later)

### Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/sreevidya-16/chat-app.git
    cd chat-app
    ```

2. Install the dependencies:

    ```sh
    npm install
    ```

3. Start the server:

    ```sh
    node index.js
    ```

4. Open your browser and navigate to `http://localhost:5000` to see the chat application in action.

## Project Structure

- **index.html:** The HTML file containing the front-end code for the chat application.
- **index.js:** The main server file, which sets up the Express server and Socket.IO communication.

## Code Explanation

### index.html

This file contains the front-end code for the chat application. It includes:
- A form to enter the username and message.
- A message area to display the chat messages.
- Tailwind CSS for styling.

### index.js

This file contains the server-side code, including:
- Setting up an Express server.
- Integrating Socket.IO for real-time communication.
- Handling events for sending and receiving messages.

## Styling

The application uses Tailwind CSS for styling. Some key styles applied include:
- A gradient background for the body.
- White containers for the form and message area, with padding, rounded corners, and shadow.
- Spacing and padding adjustments for form elements.
- A hover effect on the send button for better interactivity.
- Distinct styles for usernames and chat messages to differentiate them visually.

## How It Works

1. The user enters their username and message in the form.
2. On form submission, the username and message are sent to the server using Socket.IO.
3. The server broadcasts the message to all connected clients.
4. Each client receives the message and displays it in the message area.


## Acknowledgements

- [Node.js](https://nodejs.org/)
- [Socket.IO](https://socket.io/)
- [Tailwind CSS](https://tailwindcss.com/)

