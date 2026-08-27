# Stock Trading Platform

A full-stack stock trading web application inspired by Zerodha, built using the MERN stack. It provides a secure, interactive environment where users can manage portfolios, place stock orders, and track investments through an intuitive dashboard.

🔗 **Live Demo:** [stock-trading-platform-nine.vercel.app](https://stock-trading-platform-nine.vercel.app/)
**Login:** Username: `Demo` · Password: `Demo`

---

## Table of Contents

1. [Overview](#overview)
2. [Tech Stack](#tech-stack)
3. [Libraries Used](#libraries-used)
4. [Features](#features)
5. [Screenshots](#screenshots)
6. [Getting Started](#getting-started)
7. [Setup](#setup)
8. [Acknowledgments](#acknowledgments)
9. [License](#license)

---

## Overview

A stock trading platform clone that replicates core functionality of platforms like Zerodha, including portfolio management, order placement, and real-time dashboard tracking — built end-to-end using the MERN stack.

## Tech Stack

| Layer     | Technology |
| --------- | ---------- |
| Frontend  | React.js   |
| Backend   | Node.js, Express.js |
| Database  | MongoDB    |

## Libraries Used

| Package / Library  | Purpose                       |
| ------------------- | ----------------------------- |
| Bootstrap 5.3        | Responsive design              |
| Material UI          | UI components                  |
| Mongoose              | MongoDB object modeling        |
| Bcrypt                | Password hashing               |
| JWT                   | Authentication tokens          |
| Chart.js              | Data visualization             |
| Axios                 | HTTP client                    |
| React Router DOM      | Client-side routing            |
| Passport              | Authentication middleware      |
| CORS                  | Cross-origin resource sharing  |
| Body-Parser           | Request body parsing           |

## Features

- Secure user authentication and authorization (JWT)
- Portfolio dashboard with holdings overview
- Buy and sell stock order placement
- Order management and history
- RESTful API integration between frontend and backend
- Responsive UI across devices
- MongoDB-backed persistent data storage

## Screenshots

| Home Page                             | Dashboard                              | About Page                         |
| -------------------------------------- | --------------------------------------- | ----------------------------------- |
| ![Home](./Screenshot/Homepage.jpeg)    | ![Dashboard](./Screenshot/Dashboard.jpeg) | ![About](./Screenshot/About.jpeg) |

| Products Page                         | Pricing Page                          | Support Page                        |
| --------------------------------------- | --------------------------------------- | ------------------------------------- |
| ![Products](./Screenshot/Product.jpeg) | ![Pricing](./Screenshot/Pricing.jpeg) | ![Support](./Screenshot/Support.jpeg) |

## Getting Started

Clone the repository:

```bash
git clone https://github.com/triveninelakurthi9/StockTradingPlatform.git
```

Install dependencies for backend, dashboard, and frontend:

```bash
cd backend && npm install
cd ../dashboard && npm install
cd ../frontend && npm install
```

Create a `.env` file inside the `backend` folder:

```env
PORT=3000
MONGO_URL="your_mongodb_connection_url"
secret="your_jwt_secret"
```

Start the application:

```bash
npm start
```

## Setup

1. Navigate to `localhost:3000`.
2. Register a new user account.
3. Explore the dashboard, place orders, and manage your portfolio.

## Acknowledgments

- Built as part of a learning project while studying full-stack development with the MERN stack.
- Inspired by the Zerodha trading platform.
- Developed for educational purposes.

## License

Licensed under the [MIT License](LICENSE). See the [LICENSE](LICENSE) file for details.
