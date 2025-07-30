# 🛒 Green-Cart-MERN

A fully functional, modern grocery store web application built with the **MERN stack**, featuring **Clerk Authentication**, **Stripe Payments**, and **Vercel Deployment**. Users can buy daily essentials, and sellers can list and manage their grocery items seamlessly.

---

## 🌟 Features

- 🔐 **Clerk Authentication** for secure user login/signup
- 🛍️ **Dual Role System** – Buyers and Sellers
- 💳 **Stripe Integration** for seamless payments
- ⚡ **Vite + React** for a blazing-fast frontend
- 🧾 **Real-time Product Listings** with MongoDB
- 📦 **Seller Dashboard** to manage inventory
- 🛒 **Shopping Cart** with quantity & price management
- 🚀 **Deployed via Vercel** (frontend + backend)
- 📦 **Yarn** package manager used for consistency and speed

---

## 🖥️ Tech Stack

| Technology     | Purpose                          |
|----------------|----------------------------------|
| React (Vite)   | Frontend framework               |
| Node.js        | Backend runtime                  |
| Express.js     | Backend framework                |
| MongoDB        | Database                         |
| Clerk          | Authentication & user sessions   |
| Stripe         | Payment processing               |
| Vercel         | Hosting (Frontend & Backend)     |
| Yarn           | Package manager                  |

---

## 🚀 Getting Started

Install Dependencies
Frontend
bash
Copy
Edit
cd client
yarn install

Backend
bash
Copy
Edit
cd ../server
yarn install


3. Environment Variables
Create .env files in both client and server folders.

Example .env for Backend (/server/.env):
env
Copy
Edit
PORT=8000
MONGO_URI=your_mongodb_connection_string
CLERK_SECRET_KEY=your_clerk_secret_key
STRIPE_SECRET_KEY=your_stripe_secret_key
FRONTEND_URL=https://green-cart-frontend.vercel.app
Example .env for Frontend (/client/.env):
env
Copy
Edit
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
VITE_BACKEND_URL=https://green-cart-backend.vercel.app/api
VITE_STRIPE_PUBLISHABLE_KEY=your_stripe_publishable_key


4. Run the App Locally
Start Backend
bash
Copy
Edit
cd server
yarn dev
Start Frontend
bash
Copy
Edit
cd client
yarn dev


🌐 Live Demo
Frontend: https://green-cart-mern-client.vercel.app/
Backend: https://green-cart-mern-backend-rho.vercel.app/

📸 Screenshots
You can add screenshots here to showcase the UI and functionality.

👨‍💻 Author
Ayush Verma
MERN Stack Developer from India
LinkedIn | GitHub

🪪 License
This project is licensed under the MIT License.

🙏 Acknowledgements
Clerk.dev – For Authentication
Stripe – For Payment Gateway
MongoDB Atlas – For Cloud DB
Vercel – For Deployments
