# 🛒 Green Cart - Full Stack Grocery Delivery App

**Green Cart** is a feature-rich, responsive Full Stack Grocery Delivery Application designed to provide users with a seamless online shopping experience. It includes real-time product browsing, cart and checkout functionality, secure authentication, and a seller dashboard to manage inventory.

---

## 🌐 Live Demo

🔗 **Live Site**: [https://green-cart.vercel.app](https://greencart-deploy-8rrm.vercel.app/)

---

## 🖼️ Screenshots

### 🏠 Landing Page  

![GreenCart Screenshot](https://raw.githubusercontent.com/Om20An00/greencart-deploy-public/main/client/src/assets/1.png)



### 🛍️ Product Listing  
![Second Screenshot](https://raw.githubusercontent.com/Om20An00/greencart-deploy-public/main/client/src/assets/2.png)



### 🛒 Cart & Checkout  
![Third Screenshot](https://raw.githubusercontent.com/Om20An00/greencart-deploy-public/main/client/src/assets/3.png)



---

## 💡 Features

- 🔐 User Sign Up, Login & Auth (via Clerk or custom)
- 🛍️ Browse & Search Grocery Products
- 🛒 Add to Cart with Quantity Controls
- 💳 Checkout with Payment Options (COD / Stripe)
- 🧾 Order Summary & Confirmation
- 📈 Seller Dashboard to Add/Edit/Delete Products
- 📦 Inventory Management
- 🎨 Clean, responsive UI using TailwindCSS or Bootstrap
- 🌐 Real-time updates with Axios & API calls

---

## 🛠 Tech Stack

### Frontend:
- React.js  
- TailwindCSS / Bootstrap  


### Backend:
- Node.js  
- Express.js  
- MongoDB 
- Mongoose 

### Dev & Deployment:
- Vite / Create React App  
- Cloudinary (for image uploads)  
- Stripe (for payments)  
- dotenv  
- nodemon  
- Vercel / Render

---

## 📦 Installation & Setup

### 📥 Clone the Repositories


git clone https://github.com/Om20An00/greencart-frontend

git clone https://github.com/Om20An00/greencart-backend

🚀 Frontend Setup

cd greencart-frontend
npm install
npm run dev
🛠️ Backend Setup

cd greencart-backend
npm install
npm start
🔐 Environment Variables
Backend .env
env

MONGODB_URI=your_mongo_url

STRIPE_SECRET_KEY=your_stripe_key

CLOUDINARY_CLOUD_NAME=your_name

CLOUDINARY_API_KEY=your_key

CLOUDINARY_API_SECRET=your_secret

Frontend .env
env

VITE_BACKEND_URL=http://localhost:5000
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_key

🐳 Run with Docker (Local)
If you have Docker installed, you can run the entire app easily with Docker Compose.

### 🐳 Docker Setup Screenshot

![Docker Screenshot](https://github.com/Om20An00/greencart-deploy-public/blob/1b5e25e2e6d4953ecd489d90c95e1ce5a4acbbff/client/src/assets/docker_image.jpg?raw=true)




Steps:
Clone the repo (or your fork)

Create a .env file inside the server/ folder from .env.example and fill in your environment variables.

From the project root folder, run:

docker compose up --build
Wait for the build and containers to start.

Visit the frontend at: http://localhost:3000

Backend APIs run on: http://localhost:4000

To run Docker containers in background (detached mode):

docker compose up --build -d
To stop and remove containers:

docker compose down

🤝 Contributing / Forking
Want to contribute or build your own version?

🍴 Fork this repository

📥 Clone it to your local system

git clone https://github.com/Om20An00/greencart.git

🔧 Make your changes

✅ Push and submit a pull request

Attribution is appreciated but not required.
