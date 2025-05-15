 Clazora
Clazora is an online learning platform that connects teachers and students. It lets teachers create courses and students enroll and learn easily.

Features
Teacher and student accounts

Teachers can create and manage courses

Students can browse and join courses

Courses include videos, texts, and quizzes

Track student progress

Secure login with email and password

Works on both desktop and mobile

Technologies
Frontend: React.js

Backend: Node.js with Express

Database: MongoDB

Authentication: JWT tokens

Styling: CSS and Bootstrap

How to Run Locally
Clone the repo:

bash
Copy
Edit
git clone https://github.com/falluranium77/clazora.git
cd clazora
Install backend dependencies:

bash
Copy
Edit
cd backend
npm install
Create .env file in backend with:

ini
Copy
Edit
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
Start backend server:

bash
Copy
Edit
npm run dev
Open new terminal and install frontend dependencies:

bash
Copy
Edit
cd ../frontend
npm install
Start frontend app:

bash
Copy
Edit
npm start
Open http://localhost:3000 in your browser

Project Structure
bash
Copy
Edit
clazora/
├── backend/        # API server code
├── frontend/       # React app code
└── README.md       # This file
How to Contribute
Fork the repo

Create a branch: git checkout -b feature-name

Commit your changes

Push your branch

Open a pull request

