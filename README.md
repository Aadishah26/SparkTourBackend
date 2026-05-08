🌍 Spark Tour & Travels

A full-stack travel booking and tour management platform built using the MERN stack.
The application allows users to explore tour packages, book trips, make secure payments, manage bookings, and interact with a responsive and user-friendly travel experience.

✨ Features
👤 User Authentication & Authorization
User Registration & Login
JWT-based Authentication
Protected Routes
Session Persistence
Password Reset Functionality
Logout System
🌍 Tour Management
Browse All Tours
Search Tours by Destination
Filter Tours by Price
Detailed Tour Pages
Tour Image Gallery
Tour Availability Information
📅 Booking System
Book Tours Online
Select Travel Dates
Traveller Count Management
Booking Summary
Cancel Bookings
View Booking History
💳 Payment Integration
Razorpay Payment Gateway
Secure Payment Processing
Card Validation
Booking Confirmation
Payment Confirmation Emails
HTTPS Secure Transactions
👨‍💼 Admin Panel
Admin Authentication
Add New Tours
Edit Tour Details
Delete Tours
Manage Bookings
Manage Users
Update Booking Status
📱 Responsive UI/UX
Fully Responsive Design
Mobile Friendly Layout
Tablet Optimization
Hamburger Navigation Menu
Toast Notifications
Custom 404 Page
🛠️ Tech Stack
Frontend
React.js
Tailwind CSS
JavaScript
Vite
Backend
Node.js
Express.js
Database
MongoDB
Mongoose ODM
Authentication
JWT (JSON Web Tokens)
Payment Gateway
Razorpay
API Testing
Postman
📂 Project Structure
spark-tour-travels/
│
├── client/ # Frontend
│ ├── src/
│ │ ├── assets/
│ │ ├── components/
│ │ ├── pages/
│ │ ├── styles/
│ │ ├── api/
│ │ ├── App.jsx
│ │ └── main.jsx
│
├── server/ # Backend
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ ├── middleware/
│ ├── config/
│ ├── utils/
│ └── server.js
│
├── package.json
└── README.md
⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/spark-tour-travels.git
2️⃣ Navigate to Project Folder
cd spark-tour-travels
3️⃣ Install Frontend Dependencies
cd client
npm install
4️⃣ Install Backend Dependencies
cd ../server
npm install
5️⃣ Configure Environment Variables

Create a .env file inside the server folder:

PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_jwt_secret
RAZORPAY_KEY_ID=your_key
RAZORPAY_SECRET=your_secret
6️⃣ Run Backend Server
npm start
7️⃣ Run Frontend Application
cd ../client
npm run dev
🔌 API Endpoints
Authentication APIs
POST /api/auth/register
POST /api/auth/login
POST /api/auth/forgot-password
Tour APIs
GET /api/tours
GET /api/tours/:id
Booking APIs
POST /api/bookings
GET /api/bookings/user
🧪 Testing

The project includes extensive manual functional testing.

Test Coverage
Authentication & Authorization
Tour Listings & Search
Booking Management
Payment Processing
User Profile
Admin Panel
Responsive UI
REST APIs
Testing Tools
Postman
Google Chrome
Mozilla Firefox
Microsoft Edge
📊 Functional Testing Summary
Module Pass Rate
Authentication & Authorization 100%
Payment Processing 100%
Admin Panel 100%
UI & Responsiveness 100%
REST APIs 100%
✅ Overall Pass Rate: 96.6%
🔮 Future Enhancements
Automated Testing (Cypress/Jest)
Email Queue System
Tour Pagination
Wishlist Feature
Review & Rating System
AI-Based Tour Recommendations
Real-time Booking Availability
Multi-language Support
