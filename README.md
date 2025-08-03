# 🛒 Green Cart - Full Stack Grocery Delivery App

**Green Cart** is a feature-rich, responsive Full Stack Grocery Delivery Application designed to provide users with a seamless online shopping experience. It includes real-time product browsing, cart and checkout functionality, secure authentication, and a seller dashboard to manage inventory.

---

## 🌐 Live Demo

🔗 **Live Site**: [https://green-cart.vercel.app](https://greencart-deploy-8rrm.vercel.app/)

---

## 🖼️ Screenshots

### 🏠 Landing Page  
[<img width="1349" height="557" alt="image" src="https://github.com/user-attachments/assets/d3b68403-8006-4563-8989-0c7a65a5da30" />](https://github.com/Om20An00/greencart-deploy-public/blob/main/client/src/assets/1.png)


### 🛍️ Product Listing  
[<img width="1349" height="706" alt="image" src="https://github.com/user-attachments/assets/1b23a371-3395-46c6-aa3c-7c907a1bccc3" />](https://github.com/Om20An00/greencart-deploy-public/blob/main/client/src/assets/2.png)


### 🛒 Cart & Checkout  
[<img width="1345" height="631" alt="image" src="https://github.com/user-attachments/assets/75562e2a-b83f-40a0-ab88-d6d5f97bdce2" />](https://github.com/Om20An00/greencart-deploy-public/blob/main/client/src/assets/3.png)


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

```bash
git clone https://github.com/yourusername/greencart-frontend
git clone https://github.com/yourusername/greencart-backend

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
🤝 Contributing / Forking
Want to contribute or build your own version?

🍴 Fork this repository

📥 Clone it to your local system

git clone https://github.com/yourusername/greencart.git
🔧 Make your changes

✅ Push and submit a pull request

Attribution is appreciated but not required.
