# Real-Time Whiteboard

The Real-Time Whiteboard is a collaborative web application that allows multiple users to draw and interact with each other in real-time on a shared canvas. It leverages the power of Socket.io for real-time communication and Express.js for serving the web application.

## Features

- **Real-Time Collaboration**: Multiple users can join the same room and draw together on a shared canvas.
- **Drawing Tools**: Users can choose from various drawing tools such as pen, eraser, shapes, and colors.
- **Undo/Redo**: Supports undo and redo functionality for drawing actions.
- **Responsive Design**: The application is designed to work seamlessly across different devices and screen sizes.

## Technologies Used

- **Node.js**: Backend runtime environment.
- **Express.js**: Web application framework for Node.js used for routing and middleware.
- **Socket.io**: JavaScript library for real-time web applications, enabling bidirectional communication between clients and servers.
- **HTML5 Canvas**: Used for drawing and rendering the whiteboard.
- **EJS**: Templating engine for generating HTML markup.
- **CSS**: Styling the user interface for a pleasant user experience.

## Getting Started

### Prerequisites

- Node.js and npm installed on your machine.

### Installation

1. Clone this repository to your local machine.
   ```bash
   https://github.com/Md-Aurangzeb/real-time-whiteboard.git
2. Navigate to the project directory.
   ```bash
   cd real-time-whiteboard
3. Install dependencies using npm.
   ```bash
   npm install
5. Start the server.
   ```bash
   npm start
7. Open your web browser and go to
   http://localhost:3000


## Usage

1. Upon accessing the application, you will be redirected to a randomly generated room.
2. Share the room URL with others to invite them to join the whiteboard session.
3. Choose a drawing tool from the toolbar and start drawing on the canvas.
4. Collaborate with others in real-time by drawing and interacting with the canvas together.
