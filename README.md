#🛒  #MERN E-Commerce Website
Welcome to the MERN E-Commerce Website! This project is a modern, full-featured e-commerce application developed using the powerful MERN Stack. It provides a smooth shopping experience for users and a robust admin dashboard for efficient management.

✨ Features
🌐 User Frontend
🔐 Secure Authentication: Sign up, log in, and manage profiles using JWT-based sessions.

🛍️ Product Browsing: View and search a wide range of products with category filters.

🛒 Shopping Cart: Add to cart, update quantities, and review cart before checkout.

💳 Stripe Payment Integration: Make secure online payments.

📦 Order History: Track orders, view details, and manage returns easily.

🧑‍💼 Admin Dashboard
🛠️ Product Management: Add, update, or delete products through an intuitive interface.

🗂️ Category Management: Organize your catalog for better navigation.

📑 Order Handling: View, process, and update customer orders.

👥 User Roles: Manage users and control access levels efficiently.

🛠️ Tech Stack
MongoDB – Flexible NoSQL database.

Express.js – Lightweight backend framework.

React.js – Dynamic frontend with responsive UI.

Node.js – Backend runtime environment.

Stripe API – Payment gateway integration.

JWT – Secure authentication and session management.

📁 Folder Structure
bash
Copy
Edit
/
├── admin/        # React-based Admin Dashboard
├── backend/      # Node.js + Express Backend
├── frontend/     # React-based User Frontend
├── .gitignore
├── README.md
⚙️ Getting Started
✅ Prerequisites
Ensure you have the following installed:

Git

Node.js

npm

🔽 Clone the Repository
bash
Copy
Edit
git clone https://github.com/krishna1505/EKart.git
📦 Installation
Install dependencies for all 3 parts:

bash
Copy
Edit
cd admin
npm install

cd ../frontend
npm install

cd ../backend
npm install
🔐 Environment Variables
Set up .env files in the following folders:

admin/.env

frontend/.env

backend/.env

Add the required environment variables (API keys, database URI, JWT secrets, etc.)

🚀 Running the Project
▶️ Admin Dashboard
bash
Copy
Edit
cd admin
npm run dev
Visit: http://localhost:5174

▶️ Backend Server
bash
Copy
Edit
cd backend
npm run server
API running on: http://localhost:4000

▶️ User Frontend
bash
Copy
Edit
cd frontend
npm run dev
Visit: http://localhost:5173

🙌 Contribution
Feel free to fork this repo and contribute via PRs. Any suggestions, bug fixes, or improvements are welcome!

📄 License
This project is open-source and available under the MIT License.
