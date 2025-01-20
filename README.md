# Heaven Top Application

## 🚀 Overview
Heaven Top is a **full-stack e-commerce platform** that offers users a seamless shopping experience. It allows users to browse products, add items to their cart, and securely checkout. The application is built using **React.js** for the frontend and **Node.js with Express.js** for the backend, leveraging **MongoDB** for data storage.

## ✨ Features
- 🛍 **Product Catalog** – Browse a variety of products with detailed descriptions.
- 🛒 **Shopping Cart** – Add and manage items in the cart.
- 💳 **Secure Checkout** – Complete transactions with integrated payment gateways.
- 🔍 **Search & Filters** – Easily find products using advanced search and filters.
- 👤 **User Authentication** – Sign up, log in, and manage user profiles securely.
- 📦 **Order Tracking** – Track order status in real time.
- ⚡ **Admin Dashboard** – Manage products, orders, and users efficiently.

## 🛠 Tech Stack
### **Frontend**
- React.js
- Redux for state management
- Styled Components / Tailwind CSS

### **Backend**
- Node.js
- Express.js
- MongoDB with Mongoose
- JWT Authentication
- Stripe API for payments

### **Other Tools**
- Cloudinary (for image uploads)
- Redis (for caching)
- Docker (for containerization)
- Nodemailer (for email notifications)

## 📂 Project Structure
```
📦 HeavenTop
├── 📂 client            # Frontend (React.js)
├── 📂 server            # Backend (Node.js, Express)
│   ├── 📂 models       # Mongoose Schemas
│   ├── 📂 routes       # Express Routes
│   ├── 📂 controllers  # Business Logic
│   ├── 📂 middleware   # Authentication & Error Handling
│   ├── 📂 config       # Environment Variables & Config Files
│   ├── index.js       # Entry Point
├── 📂 public            # Static Assets
├── 📜 .env.example      # Example Environment Variables
├── 📜 package.json      # Dependencies
└── 📜 README.md         # Project Documentation
```

## ⚡ Installation & Setup
### **1️⃣ Clone the Repository**
```sh
git clone https://github.com/yourusername/HeavenTop.git
cd HeavenTop
```

### **2️⃣ Install Dependencies**
#### Backend:
```sh
cd server
npm install
```
#### Frontend:
```sh
cd client
npm install
```

### **3️⃣ Set Up Environment Variables**
Create a `.env` file in the `server` directory and add the required configurations.
```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
STRIPE_SECRET=your_stripe_api_key
CLOUDINARY_API_KEY=your_cloudinary_api_key
```

### **4️⃣ Start the Application**
#### Start the backend server:
```sh
cd server
npm start
```
#### Start the frontend:
```sh
cd client
npm start
```

The app will be live at **`http://localhost:3000`**

## 🛡 Security & Performance Enhancements
- **Helmet.js** – Protects against common vulnerabilities.
- **Rate Limiting** – Prevents API abuse.
- **Caching with Redis** – Optimizes performance.
- **Docker** – For seamless deployment.

## 📜 API Endpoints
| Method | Endpoint        | Description                  |
|--------|----------------|------------------------------|
| GET    | `/api/products` | Get all products |
| POST   | `/api/orders` | Create a new order |
| GET    | `/api/user` | Fetch user profile |

## 🤝 Contributing
Contributions are welcome! Feel free to **fork** this repository and submit a PR.

## 📧 Contact
- **Author:** Nishant Atras
- **Email:** nishantatras2000@gmail.com
- **GitHub:** [nishantatras](https://github.com/nishantatras@gmail.com)

