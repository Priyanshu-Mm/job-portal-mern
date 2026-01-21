# Job Portal App (MERN Stack)

A full-stack Job Portal web application built using the MERN
(MongoDB, Express.js, React.js, Node.js) stack.
The application allows users to browse job listings, apply for jobs,
and manage their applications efficiently.

## Features
- User Authentication using JWT (for Job Seekers and Recruiters)
- Browse and view job listings
- Apply for jobs and track applications
- Recruiters can manage posted jobs
- Secure password hashing using Bcrypt
- Responsive UI for different screen sizes

## Technologies Used
### Frontend
- React.js
- React Router
- Bootstrap

### Backend
- Node.js
- Express.js
- MongoDB (Atlas)

### Authentication
- JWT (JSON Web Tokens)
- Bcrypt

## Getting Started

Follow the steps below to run the project locally.

### Prerequisites
- Node.js installed on your system
- MongoDB Atlas account (or local MongoDB)
- Git installed

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Priyanshu-Mm/job-portal-mern.git

2. Install backend dependencies:
   cd job-portal-mern
   cd backend
   npm install

3. Install frontend dependencies
  cd ../frontend
  npm install

## Environment Variables

Create a .env file inside the backend folder and add the following:
 PORT=4000
 MONGO_URI=your_mongodb_connection_string
 JWT_SECRET=your_jwt_secret

## Run the Application
 Start the backend server:
  cd frontend
  npm run dev

## Open your browser and visit:
http://localhost:5173

## Notes
 This project is currently configured for local development.
 Deployment will be added after GitHub upload.


## Author
 Priyanshu Maurya
 GitHub: https://github.com/Priyanshu-Mm





 