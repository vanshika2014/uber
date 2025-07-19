# 🚖 Uber Clone Web App

A fully functional **Uber Clone** web application that allows users to book rides, track ride status, and manage bookings. Built with modern web technologies, this project is designed to mimic core Uber functionalities for learning and demonstration purposes.

---

## 🌐 Live Demo

👉 [Click here to view the project live](https://your-deployment-link.com)  
*(Replace with your actual live URL)*

---

## 📸 Screenshots

> Insert screenshots or demo GIFs  
> Example: ![Homepage Screenshot](./screenshots/homepage.png)

---

## 🔥 Features

- 🧭 Select pickup and drop locations
- 🗺️ Interactive map using Google Maps API
- 👤 User authentication (login/register)
- 🚗 Book and track rides in real-time
- 📜 Ride history and booking details
- 🧑‍💼 Separate Driver and User dashboards
- 🔒 Secure with JWT authentication
- 📱 Responsive mobile-friendly design

---

## 💻 Tech Stack

### Frontend:
- HTML5, CSS3, JavaScript
- Bootstrap / Tailwind CSS *(if used)*
- Google Maps JavaScript API *(for real-time map)*

### Backend:
- Node.js
- Express.js
- MongoDB with Mongoose
- JWT for authentication
- RESTful APIs

### Tools & Hosting:
- Git & GitHub
- Postman for API testing
- Render / Vercel / Netlify *(frontend hosting)*
- MongoDB Atlas *(database hosting)*

---

## 📁 Folder Structure
uber-clone/
│
├── client/ # Frontend files
│ ├── index.html
│ ├── styles/
│ └── scripts/
│
├── server/ # Backend files
│ ├── routes/
│ ├── controllers/
│ ├── models/
│ └── server.js
│
├── .env
├── package.json
└── README.md


---

## 🚀 Getting Started Locally

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/uber-clone.git
cd uber-clone
cd server
npm install

Create .env file in /server


PORT=5000
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
Start backend server


node server.js
Open frontend
Simply open client/index.html in your browser or host using Live Server.

🛠️ Functionality Overview
Feature	Description
User Auth	Register & login with JWT auth
Location Input	Google Maps autocomplete for locations
Ride Booking	Select locations, book ride, confirm driver
Ride History	View past rides
Driver Panel	Accept/reject ride requests

📈 Future Enhancements
Add real-time tracking using WebSockets

Add payment gateway integration (Razorpay/Stripe)

Add driver rating and feedback system

Mobile app version using React Native or Flutter

🙋‍♀️ About the Creator
Vanshika
📸 Instagram: tym2_fly_
💼 Passionate about web development, blockchain, and building real-world projects.

📄 License
This project is licensed under the MIT License.
Not affiliated with Uber Technologies Inc. — created for educational purposes.

🤝 Support
If you like this project, consider giving it a ⭐ on GitHub!
For feedback or collaboration, feel free to DM on Instagram or drop an issue on the repo.



---



