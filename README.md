# Stock Trading Platform – Full-Stack Stock Trading Web Application

A robust and interactive stock trading platform developed as a Zerodha-inspired clone using MERN stack. Built as part of a hands-on learning project using resources from Apna College.

---

## 📌 Project Goal

To simulate a real-time trading experience for users to practice stock investments, explore trends, and understand trading workflows through a visually rich and dynamic interface.

---

## 🚀 Key Features

- 📈 Live stock chart integration (static/mock data for simulation)
- 🧾 User portfolio management
- 🔐 Secure user authentication (JWT-based)
- 🗃️ Order placement and watchlist features
- 🎨 Interactive, responsive dashboard UI using Tailwind CSS
- 🧠 Built with modular, reusable React components

---

## 🛠️ Tech Stack

**Frontend:** React.js, Tailwind CSS, Axios  
**Backend:** Node.js, Express.js  
**Database:** MongoDB  
**Authentication:** JSON Web Tokens (JWT)

---

## 💡 How I Developed It

- Followed a structured MERN full-stack roadmap using Apna College resources
- Designed a responsive UI from scratch inspired by Zerodha’s minimal design
- Built REST APIs for user, stock, and order management
- Integrated MongoDB for data persistence and security
- Implemented state management using React hooks

---

## 📁 Folder Structure

```
investiq/
├── client/         # React frontend
│   ├── public/
│   └── src/
│       ├── components/
│       ├── pages/
│       └── App.js
├── server/         # Node.js + Express backend
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── index.js
├── dashboard/      # Dashboard UI components
├── README.md
```


---

## 🖥️ How to Run Locally

```bash
# Clone the repository
git clone https://github.com/triveninelakurthi9/investiq.git
cd investiq

# Start backend
cd server
npm install
npm start

# Start frontend
cd ../client
npm install
npm start




