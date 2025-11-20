🏠 MERN Stack Home Rental & Sales App

A full-featured Real Estate Web Application built using the MERN Stack (MongoDB, Express, React, Node.js) with Clerk Authentication and Tailwind CSS for a modern UI. This project demonstrates how to build, deploy, and scale a complete property rental and sales platform from scratch.

🚀 Project Overview
This application allows users to:
Browse properties for rent or sale
View detailed property information
Register agencie
Book properties
Make secure payments via Stripe
Manage bookings
Access admin dashboard for property management
It features a responsive design, real-time data handling, authentication, and a scalable backend.

🔧 Tech Stack
Frontend
React + Vite
Tailwind CSS
Clerk Authentication (Frontend)
Stripe Payments
Backend
Node.js
Express.js
MongoDB

Clerk Authentication (Backend)
Nodemailer
Cloudinary

🌐 Live Demo
🔗 Full App: https://nestorria-full.vercel.app/

📌 Features
User Authentication (Clerk)
Property Listings with Filters
Agency Registration
Booking System
Admin Dashboard
Add / Edit / Delete Properties
Responsive UI
Stripe Payment Integration
Email Notifications
Secure API Handling

⚙️ Installation & Setup

1️⃣ Clone the Repository
git clone <repo-url>
cd project-folder

2️⃣ Install Dependencies
Frontend
cd client
npm install
npm run dev

Backend
cd server
npm install
npm run start

🔐 Environment Variables

Frontend .env
VITE_PUBLISHABLE_KEY=
VITE_CURRENCY=
VITE_BACKEND_URL=

Backend .env
MONGODB_URI=
CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
CLERK_WEBHOOK=
CLDN_NAME=
CLDN_API_KEY=
CLDN_API_SECRET=
SMTP_USER=
SMTP_PASS=
SENDER_EMAIL=
STRIPE_SECRET_KEY=
STRIPE_PUBLISHABLE_KEY=
STRIPE_WEBHOOK_SECRETS=

📦 Deployment
Frontend: Vercel
Backend: Render / Vercel
Database: MongoDB Atlas
Ensure all environment variables are configured before deployment.

❤️ Acknowledgements
Thanks for checking out this project! If you find it useful, consider giving it a ⭐ on GitHub and supporting the creator.
Happy Coding! 🚀
