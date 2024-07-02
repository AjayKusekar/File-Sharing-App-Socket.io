# File Sharing App

This file-sharing application allows users to share files in real-time using Socket.io, Node.js, and Express. The process involves creating a room ID by the sender, which is then shared with the receiver along with a link. The receiver uses this link and room ID to receive the files.

## Features

- Real-time file sharing using Socket.io
- Simple and intuitive user interface
- Secure room-based file transfer

## How It Works

1. **Sender** creates a room ID.
2. **Sender** sends the link and room ID to the receiver.
3. **Receiver** opens the link and enters the room ID to receive the files.

## Setup and Installation

To get started with the file-sharing app, follow these steps:

### Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/AjayKusekar/File-Sharing-App-Socket.io.git
    cd File-Sharing-App-Socket.io
    ```

2. Install the dependencies:

    ```bash
    npm install
    ```

3. Start the server:

    ```bash
    npm start
    ```

4. Open your browser and navigate to `http://localhost:5000` to use the app.

## Usage

### Sender

1. Open `http://localhost:5000`.
2. Create a room ID by clicking the "Create Room" button.
3. Share the link and room ID with the receiver.

### Receiver

1. Open `http://localhost:5000/receiver.html`.
2. Enter the room ID provided by the sender.
3. Receive the files.

## Technologies Used

- Node.js
- Express
- Socket.io

