🍽️ Restaurant-Application
A full-stack web application for discovering restaurants, browsing menus, placing orders, and managing restaurant operations.

🚀 Overview
This app allows users to:

Discover and filter restaurants by dietary preferences

Browse menus, add items to cart, and place orders

View order history and leave reviews

Administer restaurants and users through dedicated dashboards

🛠️ Tech Stack
Frontend: React, Context API, Tailwind CSS, Vite

Backend: Node.js, Express, MongoDB

Authentication: Passport.js

Architecture: RESTful APIs

🔑 Core Features
✅ User authentication and registration

🔍 Restaurant browsing with dietary filters

🛒 Add-to-cart and order placement

📦 Order history and status tracking

⚙️ Admin dashboard (manage users & restaurants)

🧑‍🍳 Owner dashboard (manage menus & orders)

🌟 Ratings and review system

📱 Fully responsive UI with reusable components

📦 Folder Structure
bash
Copy
Edit
Restaurant-Application/
  client/         # React frontend
  server/         # Node.js/Express backend
  shared/         # Shared schemas/utilities
⚙️ Getting Started
1. Prerequisites
Node.js (v14 or higher)

npm or yarn

MongoDB (local or cloud)

2. Setup Instructions
Clone the repository

bash
Copy
Edit
git clone https://github.com/your-username/Restaurant-Application.git
cd Restaurant-Application
Configure environment variables

Copy .env.example to .env inside the server/ folder

Fill in your database URI and other config values

Install dependencies

Backend:

bash
Copy
Edit
cd server
npm install
Frontend:

bash
Copy
Edit
cd ../client
npm install
Start development servers

Backend:

bash
Copy
Edit
cd server
npm run dev
Frontend:

bash
Copy
Edit
cd ../client
npm run dev
Visit the app

Open http://localhost:5173 in your browser
