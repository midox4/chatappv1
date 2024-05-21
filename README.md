MERN Chat Application
This is a real-time chat application built using the MERN stack (MongoDB, Express, React, Node.js) with Socket.io for real-time messaging.

Features
Real-time messaging
Persistent chat history
User-friendly interface
MongoDB for storing messages
Socket.io for real-time communication
Getting Started
Prerequisites
Make sure you have the following installed on your system:

Node.js
npm (Node Package Manager)
MongoDB
Installation
Clone the repository:

sh
Copier le code
git clone https://github.com/yourusername/mern-chat-app.git
cd mern-chat-app
Install server dependencies:

sh
Copier le code
npm install
Install client dependencies:

sh
Copier le code
cd client
npm install
cd ..
Set up MongoDB:

Make sure your MongoDB server is running. By default, the app connects to a local MongoDB instance:

sh
Copier le code
mongod
Running the Application
Start the server:

sh
Copier le code
npm run dev
Start the client:

Open a new terminal window/tab, and run:

sh
Copier le code
cd client
npm start
Access the application:

Open your web browser and navigate to http://localhost:3000.

Project Structure
server.js: Entry point for the Node.js server.
/client: Contains the React frontend code.
/models: Contains the Mongoose schema and model for chat messages.
API Endpoints
GET /: Health check endpoint to verify the server is running.
GET /messages: Fetches all chat messages from the database.
Socket.io Events
connection: Triggered when a new client connects.
disconnect: Triggered when a client disconnects.
chat message: Handles incoming chat messages and broadcasts them to all connected clients.
Built With
MongoDB
Express
React
Node.js
Socket.io
Contributing
Contributions are welcome! Please open an issue or submit a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments
Thanks to the developers of the technologies used in this project.
