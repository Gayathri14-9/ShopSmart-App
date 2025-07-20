🛒 ShopSmart – Your Digital Grocery Store Experience
ShopSmart is a full-stack MERN (MongoDB, Express.js, React, Node.js) web application that empowers grocery store admins to efficiently manage products, categories, and inventory through a secure, responsive dashboard.

✨ Features
🔐 Admin Login/Signup for secure access

🗂️ Category Management – Create and organize product categories

📦 Product Management – Add, update, delete, and view items

📊 Inventory Display – Real-time product inventory status

⚙️ Protected Routes – Only logged-in admins can access dashboard

📱 Responsive Design for mobile and desktop views

🧰 Tech Stack
Frontend	Backend	Database	Tools
React.js	Node.js, Express	MongoDB	Postman, Git, VSCode
React Router DOM		Mongoose	dotenv, bcrypt

📁 Folder Structure
pgsql
Copy
Edit
ShopSmart/
├── Backend/
│   ├── index.js
│   ├── db/
│   │   ├── connect.js
│   │   ├── schema.js
│   │   └── products.js
│   └── package.json
├── Frontend/
│   ├── public/
│   ├── src/
│   │   ├── admin_components/
│   │   │   ├── AdminLogin.js
│   │   │   ├── AdminSignup.js
│   │   │   ├── AddProduct/
│   │   │   ├── Update/
│   │   │   ├── Orders/
│   │   │   └── AdminNavbar.js
│   │   └── App.js
│   └── package.json
🚀 Getting Started
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/yourusername/ShopSmart.git
cd ShopSmart
2. Backend Setup
bash
Copy
Edit
cd Backend
npm install
Create a .env file and add:

env
Copy
Edit
MONGO_URI=your_mongodb_connection_string
PORT=5000
Run the server:

bash
Copy
Edit
node index.js
3. Frontend Setup
bash
Copy
Edit
cd ../Frontend
npm install
npm start
Visit: http://localhost:3000

DOCUMENTATION:
https://drive.google.com/drive/folders/1XqFDxQJ-jvc6Q9HX_sIIpHzD7PyNNpJi?usp=sharing

DEMO LINK:
https://drive.google.com/file/d/1QnyTFia9dIVgbRixdGQnFATQ4qc-ChrZ/view?usp=drivesdk
