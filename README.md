Scribly 📝
Scribly is a simple note-taking app I built to keep things straightforward and clutter-free. No fancy features, just a clean place to jot down your thoughts quickly.

What it does
Lets you create, edit, delete, and view notes easily

Simple, clean interface without distractions

Stores your notes safely with MongoDB

Backend API built with Express

Frontend using React and TailwindCSS

Basic rate limiting for some peace of mind

Tech Stack
Frontend: React,TailwindCSS, DaisyUI, React Router, Axios

Backend: Node.js, Express, MongoDB (Mongoose), Rate Limiter, CORS

Getting started
Clone this repo:

bash
Copy
Edit
git clone https://github.com/hamza/scribly.git
cd scribly
Install dependencies:

bash
Copy
Edit
npm install
Create a .env file in the backend folder (or root if you prefer) with your MongoDB connection string and port:

env
Copy
Edit
MONGO_URL=your_mongo_connection_string
PORT=5001
Start the app:

bash
Copy
Edit
npm run start
Then open your browser at http://localhost:5001 and start taking notes!

Screenshot
<img width="2869" height="1555" alt="Screenshot 2025-07-18 144245" src="https://github.com/user-attachments/assets/727b802c-3a31-47be-8dfc-563a2e7c8b53" />


