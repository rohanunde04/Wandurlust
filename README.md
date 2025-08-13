# Wandurlust
This project report presents the development of WanderLust, a modern and user-friendly web application designed to facilitate travel accommodation discovery and booking. 


🌍 WanderLust – MERN Travel Blog Website
WanderLust is a full-stack travel blog platform built with the MERN stack (MongoDB, Express.js, React, Node.js) where users can explore, share, and review travel destinations. It provides an intuitive interface for browsing listings, reading reviews, and contributing personal travel experiences.

🔗 Live Demo: WanderLust on Render

✨ Features
Browse Travel Listings – View destinations with detailed descriptions and images.

User Authentication – Secure signup, login, and session handling.

Add & Manage Listings – Authenticated users can create, edit, and delete their travel posts.

Reviews & Ratings – Leave feedback on destinations with a star-rating system.

Responsive UI – Mobile-friendly design with modern styling.

Image Uploads – Cloud storage support for user-submitted photos.

🛠️ Tech Stack
Frontend: HTML, CSS, EJS templating, JavaScript

Backend: Node.js, Express.js

Database: MongoDB with Mongoose ODM

Authentication: Passport.js & Express-Session

Image Hosting: Cloudinary integration

Deployment: Render

📂 Project Structure
controllers/ – Handles business logic for listings, users, and reviews.

models/ – Mongoose schemas for Listings, Users, and Reviews.

routes/ – API and page routes for application functionality.

public/ – Static assets including CSS and client-side JavaScript.

views/ – EJS templates for dynamic server-side rendering.

init/ – Data seeding scripts.

🚀 Getting Started
Clone the repository

bash
Copy
Edit
git clone https://github.com/your-username/project-wanderlust.git
cd project-wanderlust-main
Install dependencies

bash
Copy
Edit
npm install
Configure environment variables
Create a .env file with:

env
Copy
Edit
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_KEY=your_key
CLOUDINARY_SECRET=your_secret
MONGO_URI=your_mongodb_connection
SESSION_SECRET=your_session_secret
Run the application

bash
Copy
Edit
npm start
Visit http://localhost:3000 in your browser.

📌 Future Enhancements
Add map integration for geolocation.

Implement like/favorite feature for destinations.

Enable social media sharing for listings.
