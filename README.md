Collaborative Whiteboard Application
A real-time collaborative whiteboard application built with React, Node.js, Socket.IO, TailwindCSS, MongoDB, JWT, Express, RoughJS, and Perfect Freehand. This application allows multiple users to draw simultaneously, share canvases, and collaborate seamlessly with a variety of drawing tools and features.
Features

Real-Time Collaboration: Multiple users can draw on the same canvas simultaneously using Socket.IO for real-time updates.
Drawing Tools: Includes brush, line, rectangle, circle, arrow, and text with customizable colors and sizes.
Natural Drawing Effects: Utilizes RoughJS and Perfect Freehand for smooth and natural drawing experiences.
Undo/Redo: Supports undo and redo operations for easy editing.
Save/Load & Sharing: Save canvas states, load previous drawings, and share canvases with others.
User Authentication: Secure login system using JWT for session management.
Backend Management: Node.js, Express, and MongoDB handle session data and drawing states efficiently.

Tech Stack

Frontend: React, TailwindCSS, RoughJS, Perfect Freehand
Backend: Node.js, Express, MongoDB
Real-Time Communication: Socket.IO
Authentication: JWT

Installation
Prerequisites

Node.js (v16 or higher)
MongoDB (local or cloud instance)
Git

Steps

Clone the Repository:
git clone https://github.com/yourusername/collab-whiteboard.git
cd collab-whiteboard


Install Dependencies:

For the backend:cd server
npm install


For the frontend:cd ../client
npm install




Set Up Environment Variables:

Create a .env file in the server directory with the following:MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
PORT=5000


Create a .env file in the client directory with:REACT_APP_API_URL=http://localhost:5000
REACT_APP_SOCKET_URL=http://localhost:5000




Run the Application:

Start the backend server:cd server
npm start


Start the frontend:cd ../client
npm start




Access the Application:

Open your browser and navigate to http://localhost:3000.



Usage

Sign Up/Login: Create an account or log in to access the whiteboard.
Create or Join a Canvas: Start a new canvas or join an existing one using a shared link.
Draw and Collaborate: Use the toolbar to select tools, adjust colors/sizes, and draw with others in real time.
Save and Share: Save your canvas state or share it with collaborators.
Undo/Redo: Use the undo/redo buttons to correct mistakes.

Project Structure
collab-whiteboard/
├── client/                # React frontend
│   ├── src/
│   │   ├── components/    # Reusable React components
│   │   ├── pages/         # Page components (e.g., Whiteboard, Login)
│   │   ├── App.js         # Main app component
│   │   └── ...
├── server/                # Node.js/Express backend
│   ├── routes/            # API routes
│   ├── models/            # MongoDB schemas
│   ├── socket/            # Socket.IO logic
│   └── ...
├── README.md              # Project documentation
└── ...

Contributing
Contributions are welcome! Please follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature/your-feature).
Commit your changes (git commit -m 'Add your feature').
Push to the branch (git push origin feature/your-feature).
Open a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.
Contact
For questions or feedback, feel free to reach out via GitHub Issues.

Built with ❤️ by Laddu Kumar Roy
