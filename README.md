# Stock Trading Simulator (Zerodha Clone)

## Overview
This is a full-stack stock trading simulation web application inspired by platforms like Zerodha. 
The application allows users to simulate buying and selling stocks, manage portfolios, and track 
virtual investments in real time.

## Features
- User authentication using JWT
- Buy and sell stock simulation
- Portfolio tracking
- Watchlist management
- Responsive user interface

## Tech Stack
Frontend:
- React.js
- HTML, CSS, JavaScript

Backend:
- Node.js
- Express.js

Database:
- MongoDB (Atlas)

## Project Architecture
- Frontend communicates with backend through REST APIs
- Backend handles authentication, business logic, and database operations
- MongoDB stores users, transactions, and portfolio data

## How to Run the Project

### Backend
1. Navigate to backend folder
2. Install dependencies:
   npm install
3. Create a `.env` file with:
   PORT=5000  
   MONGO_URI=your_mongodb_connection_string  
   JWT_SECRET=your_secret_key
4. Start server:
   npm start

### Frontend
1. Navigate to frontend folder
2. Install dependencies:
   npm install
3. Start application:
   npm start

## Learning Outcomes
- Hands-on experience with MERN stack
- Understanding REST APIs and authentication
- Database schema design and integration
- Full-stack application development





