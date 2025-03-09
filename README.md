GrabIt - Online Auction Platform

Welcome to GrabIt, a full-stack auction platform where users can participate as Bidders or Auctioneers. The platform allows real-time interactions, profile management, and dynamic bidding functionalities.

🚀 Tech Stack

Frontend:

HTML / CSS

Bootstrap / Tailwind CSS (when needed)

JavaScript

React.js

Backend:

Node.js

Express.js

Database:

MongoDB (for storing user profiles, auctions, and bids)

API Testing & Development:

Postman (for testing API endpoints)

🎯 Features

👥 User Profiles

Two user types: Bidder & Auctioneer

Edit & update profile in real-time

📢 Auction System

Auctioneers can create, edit, and delete auctions

Bidders can place bids and modify them before the auction closes

Real-time bidding updates using WebSockets

🔐 Authentication & Security

User authentication & authorization with JWT

Secure password storage using bcrypt

📡 Real-Time Features

Live updates for bid changes

Dynamic UI updates with React.js

🛠 Installation & Setup

1️⃣ Clone the Repository

git clone https://github.com/Vedansh-Shukla/GrabIt_Auction cd GrabIt

2️⃣ Install Dependencies

Install frontend dependencies
cd client npm install

Install backend dependencies
cd ../server npm install

3️⃣ Setup Environment Variables Create a .env file in the server directory with the following details:

MONGO_URI=your_mongodb_connection_string JWT_SECRET=your_secret_key PORT=5000

4️⃣ Run the Application

Start backend server
cd server npm start

Start frontend
cd ../client npm start

🔗 API Endpoints

Method

Endpoint

Description

POST

/api/auth/register

Register a new user

POST

/api/auth/login

User login

GET

/api/auctions

Get all auctions

POST

/api/auctions

Create a new auction

PUT

/api/auctions/:id

Edit an auction

DELETE

/api/auctions/:id

Delete an auction

POST

/api/bids

Place a bid

🛠 Tools & Libraries

Mongoose - For MongoDB object modeling

JWT - Authentication & authorization

Bcrypt - Password hashing

Socket.io - Real-time bid updates

📌 Future Enhancements

Implement admin panel for better auction management

Add payment gateway integration for seamless transactions

Enable email notifications for auction updates

🤝 Contributing

We welcome contributions! Feel free to fork this repository and submit a pull request.

📞 Contact

For any queries or collaboration, reach out at: vedanshshukla04@gmail.com

Happy Bidding!
