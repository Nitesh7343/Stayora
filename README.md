Stayora 🏡

A Full-Stack Property Booking Platform

Stayora is a full-stack property booking platform inspired by Airbnb where users can explore properties, book stays, and make secure payments. Hosts can list their properties, manage bookings, and interact with travelers through reviews and ratings.

The platform provides secure authentication, email verification via OTP, image uploads, and an integrated payment gateway.

⸻

🚀 Features

🔐 Authentication & Security
	•	User registration and login
	•	Email verification via OTP
	•	Password reset with OTP
	•	JWT-based authentication
	•	Secure cookie-based sessions
	•	Role-based access control (Traveler / Host)

🏡 Property Listings
	•	Create and manage property listings
	•	Upload listing images
	•	Property descriptions, price, location, and amenities
	•	Cloud image hosting with Cloudinary

📅 Booking System
	•	Date-based booking system
	•	Automatic conflict detection for overlapping bookings
	•	Booking management dashboard

💳 Payment Integration
	•	Razorpay payment gateway integration
	•	Secure payment verification
	•	Test payment support for development
	•	Booking confirmation after successful payment

⭐ Reviews & Ratings
	•	Travelers can review properties
	•	Rating system for listings
	•	One review per user per listing

📊 Dashboard
	•	Host dashboard to manage listings
	•	Traveler dashboard to manage bookings
	•	Booking history and status tracking

⸻

🛠 Tech Stack

Backend
	•	Node.js
	•	Express.js

Frontend
	•	EJS Templates
	•	Bootstrap
	•	JavaScript

Database
	•	MongoDB Atlas
	•	Mongoose ODM

Third-Party Services
	•	Razorpay – Payment Gateway
	•	Cloudinary – Image Hosting
	•	Brevo – Email OTP service

Authentication
	•	JSON Web Tokens (JWT)
	•	Cookie-based authentication


  📂 Project Structure


  Stayora
│
├── config
│   ├── db.js
│   ├── mailer.js
│   ├── razorpay.js
│   └── cloudinary.js
│
├── models
│   ├── user.js
│   ├── listing.js
│   ├── booking.js
│   └── review.js
│
├── routes
│   ├── auth.js
│   ├── listings.js
│   ├── bookings.js
│   ├── reviews.js
│   └── dashboard.js
│
├── middleware
│   ├── auth.js
│   ├── validate.js
│   └── errorHandler.js
│
├── utils
│
├── views
│
├── public
│
├── schema.js
├── app.js
└── package.json



⚙️ Installation
1️⃣ Clone the Repository
git clone https://github.com/Nitesh7343/Stayora


2️⃣ Navigate to Project Directory
cd stayora

3️⃣ Install Dependencies
npm install

4️⃣ Create Environment Variables
NODE_ENV=development
PORT=8080

MONGO_URL=your_mongodb_connection_string

JWT_SECRET=your_jwt_secret
JWT_EXPIRES_IN=7d
COOKIE_NAME=token

# Cloudinary
CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=

# Razorpay
RAZORPAY_KEY_ID=
RAZORPAY_KEY_SECRET=

# Brevo Email
BREVO_API_KEY=
EMAIL_FROM_NAME=Stayora
EMAIL_FROM_ADDRESS=your_email


5️⃣ Start the Server
npm run dev

Server will run on: http://localhost:8080

💳 Razorpay Test Payment
Card Number: 4111 1111 1111 1111
Expiry Date: 12/30
CVV: 123
OTP: 123456

Or test UPI ID:success@razorpay


🔒 Security Features
	•	Password hashing with bcrypt
	•	JWT authentication
	•	Secure HTTP cookies
	•	Email verification
	•	Payment signature verification


🔮 Future Improvements
	•	Google OAuth login
	•	Map-based property search
	•	Real-time booking availability
	•	Stripe payment integration
	•	Mobile responsive UI improvements
	•	Admin panel for moderation



  👨‍💻 Author

Nitesh Singh

B.Tech Computer Science Student

GitHub:
https://github.com/Nitesh7343

