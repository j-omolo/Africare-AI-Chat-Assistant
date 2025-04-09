Africare-AI-Chat-Assistant
A cutting-edge, real-time chat app built with React (Vite) and powered by OpenAI’s GPT-3.5 API. Styled with Tailwind CSS for a modern, responsive user interface.

Key Features
🎯 Real-time chat functionality

🎨 Sleek, responsive UI crafted with Tailwind CSS

🤖 Powered by OpenAI’s GPT-3.5 API

⚡ Fast and efficient with Vite

🔄 Auto-scrolling for smooth message flow

💬 Elegant chat bubbles with clear user/AI distinction

🌈 Smooth loading animations and transitions

Technology Stack
Frontend:

React (Vite)

Tailwind CSS

Heroicons

Headless UI

Backend:

Node.js

Express

OpenAI API

CORS

Dotenv

Getting Started
Prerequisites
Node.js (v14 or higher)

npm or yarn

OpenAI API key

Installation Instructions
Clone the repository:

bash
Copy
Edit
git clone https://github.com/j-omolo/Africare-AI-Chat-Assistant.git
cd Africare-AI-Chat-Assistant
Install Frontend Dependencies:

bash
Copy
Edit
cd frontend
npm
Install Backend Dependencies:

bash
Copy
Edit
cd ../backend
npm
Set Up Environment Variables:

Create a .env file in the backend directory:

bash
Copy
Edit
PORT=3000
OPENAI_API_KEY=your_openai_api_key_here
Running the Application
Start the Backend Server:

bash
Copy
Edit
cd backend
npm dev
The server will be running at http://localhost:3000

Start the Frontend Development Server:

bash
Copy
Edit
cd frontend
npm dev
The frontend will be available at http://localhost:5173

How to Use
Open your browser and go to http://localhost:5173

Begin interacting with the AI assistant by typing in the message input box.

Hit Enter or click the send button to submit your message.

The AI will respond with relevant, intelligent answers based on your input.

Project Structure
lua
Copy
Edit
africare-ai-chat/
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   │   ├── Chat.jsx
│   │   │   └── ChatMessage.jsx
│   │   ├── App.jsx
│   │   └── main.jsx
│   ├── package.json
│   └── vite.config.js
│
└── backend/
    ├── server.js
    ├── package.json
    └── .env
Contributing
Fork the repository

Create a new feature branch (git checkout -b feature/new-feature)

Commit your changes (git commit -m 'Add new feature')

Push your branch (git push origin feature/new-feature)

Open a Pull Request

License
This project is licensed under the MIT License. See the LICENSE file for more details.

Acknowledgments
Thanks to OpenAI for providing the GPT-3.5 API

Tailwind CSS for the fantastic design utilities

The React and Vite teams for building such great developer tools