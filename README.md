Google Sheets Integration Project

This project is designed to provide seamless integration with Google Sheets using a robust full-stack architecture. It features a modern frontend built with React and Vite and a backend powered by Node.js, Express.js, and MongoDB.

Table of Contents

Features

Tech Stack

Setup Instructions

Prerequisites

Installation

Usage

Project Structure

Contributing

License

Features

Google Sheets Integration: Perform CRUD operations with Google Sheets data.

Modern UI: Built with React and styled for a sleek user experience.

Scalable Backend: Node.js and Express.js backend with MongoDB for data persistence.

Responsive Design: Optimized for all screen sizes.

Tech Stack

Frontend: React, Vite

Backend: Node.js, Express.js

Database: MongoDB

Setup Instructions

Prerequisites

Node.js (v16 or higher recommended)

MongoDB (local or cloud instance)

Git

Installation

Clone the Repository:

git clone <repository-url>
cd google-sheets

Install Dependencies:

Navigate to the client directory and install frontend dependencies:

cd client
npm install

Navigate to the server directory and install backend dependencies:

cd ../server
npm install

Environment Variables:

Create a .env file in the server directory and configure the following variables:

PORT=5000
MONGODB_URI=<your-mongodb-uri>
GOOGLE_API_KEY=<your-google-api-key>

Start the Development Servers:

Frontend:

cd client
npm run dev

Backend:

cd ../server
npm start

Access the Application:
Open your browser and navigate to http://localhost:3000 (default React app port).

Usage

Authenticate with your Google account to link Google Sheets.

Perform operations like reading, writing, and updating data in Google Sheets directly from the app.

Project Structure

google-sheets/
├── client/          # Frontend code (React + Vite)
├── server/          # Backend code (Node.js + Express.js)
├── .prettierrc      # Prettier configuration
├── .git/            # Git version control

Contributing

Contributions are welcome! Please follow these steps:

Fork the repository.

Create a new branch (git checkout -b feature-branch).

Commit your changes (git commit -m 'Add feature').

Push to the branch (git push origin feature-branch).

Create a Pull Request.

License

This project is licensed under the MIT License. See the LICENSE file for details.

