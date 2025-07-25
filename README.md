# 🍔 MERN Food Delivery App

A full-stack food delivery application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). The app includes authentication, user roles (admin, customer, restaurant), dynamic menus, and order management.

## 📁 Project Structure

```
kruparaju-79-food-delivery-app-mern/
├── client/          # React frontend
└── server/          # Express + Node backend
```

---

## 🚀 Features

- 🔐 Authentication (Login/Register)
- 👤 Roles: Admin, Customer, Restaurant
- 🍽️ View and manage restaurant menus
- 🛒 Cart and checkout for customers
- 📊 Admin dashboard to manage users, restaurants, products, and orders
- 📦 Restaurant dashboard to manage own products and orders

---

## 🛠️ Tech Stack

- **Frontend**: React.js, CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Deployment Ready**: `vercel.json` provided

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/KrupaRaju-79/Food-delivery-app-MERN.git
cd kruparaju-79-food-delivery-app-mern
```

### 2. Install Backend Dependencies

```bash
cd server
npm install
```

Create a `.env` file inside the `server/` directory:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

Start the backend:

```bash
node index.js
```

### 3. Install Frontend Dependencies

Open a new terminal window and run:

```bash
cd client
npm install
npm start
```

This will start the React development server at `http://localhost:3000`.

---

## ✅ Scripts

### Client

```bash
cd client
npm start          # Run React app
npm test           # Run tests
npm run build      # Build for production
```

### Server

```bash
cd server
node index.js      # Run backend
```

---

## 🔧 Deployment

### Frontend: Vercel

- Ensure `vercel.json` is correctly set up.
- Push `client/` to Vercel via CLI or GitHub integration.

### Backend: Render / Railway / Vercel Serverless

- Host MongoDB on MongoDB Atlas.
- Deploy `server/` using your preferred Node.js hosting (like [Render](https://render.com) or [Railway](https://railway.app)).

---

## 📂 Folder Highlights

### `/client`
- `src/components/` – Reusable UI components (Navbar, Footer, etc.)
- `src/pages/` – Main pages grouped by role (`admin/`, `customer/`, `restaurant/`)
- `src/context/` – Context API for global state
- `src/styles/` – All CSS files for pages/components

### `/server`
- `index.js` – Entry point
- `Schema.js` – MongoDB models and schema
- `vercel.json` – Serverless config (for deployment)

---

## 🙌 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

---

## 📄 License

[MIT](LICENSE)

---

## 👤 Author

**Krupa Raju Achchana**

> Made with 💻 and ❤️
