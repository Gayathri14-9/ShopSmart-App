# 🛒 ShopSmart – Your Digital Grocery Store Experience

**ShopSmart** is a full-stack grocery admin dashboard built using the **MERN stack (MongoDB, Express.js, React, Node.js)**. It allows store administrators to manage products, categories, and inventory through a clean and responsive interface.

---

## 🧑‍💻 Tech Stack

- **Frontend:** React.js, React Router DOM, CSS  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB with Mongoose  
- **Tools:** Git, Postman, dotenv, bcrypt

---

## ✨ Key Features

- 🔐 Admin login and signup  
- 📦 Add, update, delete products  
- 🗂️ Manage product categories  
- 📊 Display real-time inventory  
- 🚫 Protected admin-only routes  
- 📱 Fully responsive UI

---

## 📁 Folder Structure

ShopSmart/
├── Backend/
│ ├── index.js
│ ├── db/
│ │ ├── connect.js
│ │ ├── schema.js
│ │ └── products.js
├── Frontend/
│ ├── public/
│ ├── src/
│ │ ├── admin_components/
│ │ │ ├── AdminLogin.js
│ │ │ ├── AdminSignup.js
│ │ │ ├── AddProduct/
│ │ │ ├── Update/
│ │ │ ├── Orders/
│ │ │ └── AdminNavbar.js
│ │ └── App.js

yaml
Copy
Edit

---

## ⚙️ Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/ShopSmart.git
cd ShopSmart
2️⃣ Backend Setup
bash
Copy
Edit
cd Backend
npm install
🛠️ Create a .env file in the Backend directory with the following:

env
Copy
Edit
MONGO_URI=your_mongodb_connection_string
PORT=5000
🚀 Start the backend server:

bash
Copy
Edit
node index.js
3️⃣ Frontend Setup
bash
Copy
Edit
cd ../Frontend
npm install
npm start
🌐 Visit the frontend at:
http://localhost:3000



DOCUMENTATION:
https://drive.google.com/drive/folders/1XqFDxQJ-jvc6Q9HX_sIIpHzD7PyNNpJi?usp=sharing

DEMO LINK:
https://drive.google.com/file/d/1QnyTFia9dIVgbRixdGQnFATQ4qc-ChrZ/view?usp=drivesdk
