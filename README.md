# CodeCollab -- Real-Time Collaborative Coding Platform

CodeCollab is a real-time collaborative coding platform where multiple
users can join a room and write code together. It allows developers to
collaborate instantly, share ideas, and work on coding problems in real
time.

## Live Demo

Frontend\
https://code-colab-real-time-code-editor.onrender.com/

## Features

-   Real-time collaborative code editing
-   Room based coding sessions
-   Multiple users can join the same room
-   Live code synchronization
-   Clean and simple UI
-   Unique room ID generation
-   Toast notifications for actions
-   Real-time communication using WebSockets

## Tech Stack

### Frontend

-   React.js
-   HTML5
-   CSS3
-   JavaScript

### Backend

-   Node.js
-   Express.js
-   WebSockets / Socket.io

### Deployment

-   Render

### Version Control

-   Git & GitHub

## Project Structure

    CodeCollab
    │
    ├── public
    │── src
    │       ├── components
    │       ├── pages
    │       ├── App.js
    │       └── index.js
    │
    │── server.js
    │── package.json
    │── .env
    └── README.md

## Installation

Clone the repository

    git clone https://github.com/arjun5354/code-colab.git

Go to the project directory

    cd code-colab

## Backend Setup

    npm install
    npm run server:prod

Server will run on

    http://localhost:5000

## Frontend Setup

    npm run start:front

Frontend will run on

    http://localhost:3000

## Environment Variables

Create a `.env` file in backend folder.

Example:

    REACT_APP_BACKEND_URL=Your Backend Link(http://localhost:5000 - For Local Setup)

## How It Works

1.  User enters a username.
2.  A new room is created or an existing room is joined.
3.  All users connected to the room can edit code simultaneously.
4.  Changes are broadcast to all connected users in real time using
    WebSockets.



## Author

Arjun Nayak\
BTech CSE -- Brainware University\
Kolkata, India

⭐ If you like this project, give it a star on GitHub.