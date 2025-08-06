# 🕉️ Santosh Incense – E-commerce Website

Santosh Incense is a modern and responsive e-commerce web application designed for selling incense products online. Built with a focus on performance and scalability, the project follows a clean client-server architecture using **React (Vite)** for the frontend and **JavaScript (Node.js/Express)** for the backend.

## 📁 Project Structure

```
santosh_incense/
├── client/         # Frontend (React + Vite)
├── server/         # Backend (Node.js + Express)
└── README.md
```

## 🚀 Tech Stack

### Frontend (`client/`)

- React.js (with Vite)
- JavaScript (ES6+)
- React Router
- TailwindCSS or CSS Modules (optional)
- Axios for API communication

### Backend (`server/`)

- Node.js
- Express.js
- MongoDB / JSON (for mock data)
- CORS, dotenv, body-parser

## 🛠️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/harshil-prajapati/santosh_incense.git
cd santosh_incense
```

### 2. Setup Frontend (Client)

```bash
cd client
npm install
npm run dev
```

Frontend will run at: `http://localhost:5173/`

### 3. Setup Backend (Server)

```bash
cd server
npm install
node index.js
```

Backend will run at: `http://localhost:5000/` (or as defined in `.env`)

## 🔗 API Endpoints (Examples)

- **GET** `/api/products`  
  Returns a list of incense products.

- **POST** `/api/order`  
  Place an order with user and product details.

## 📌 Features

- 🛒 Product listing, filtering, and search
- 🧘 Add to Cart and Checkout functionality
- 🧾 Order management and confirmation
- 📱 Fully responsive design
- 🔐 Basic authentication (optional)

## 📷 Screenshots


## 🙏 Acknowledgments

Made with ❤️ for **Santosh Incense** by **Harshil Prajapati** and **Bhaumik Prajapati**.
