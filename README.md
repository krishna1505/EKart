<div align="center">
  <h1>🛒 MERN E-Commerce Website</h1>
  <p><strong>A modern, full-featured e-commerce app built using the MERN Stack with user & admin support.</strong></p>
</div>

<hr>

<h2>✨ Features</h2>

<h3>🌐 User Frontend</h3>
<ul>
  <li>🔐 <strong>Secure Authentication</strong>: Sign up, log in, and manage profiles using JWT-based sessions.</li>
  <li>🛍️ <strong>Product Browsing</strong>: View and search a wide range of products with category filters.</li>
  <li>🛒 <strong>Shopping Cart</strong>: Add to cart, update quantities, and review cart before checkout.</li>
  <li>💳 <strong>Stripe Payment Integration</strong>: Make secure online payments.</li>
  <li>📦 <strong>Order History</strong>: Track orders, view details, and manage returns easily.</li>
</ul>

<h3>🧑‍💼 Admin Dashboard</h3>
<ul>
  <li>🛠️ <strong>Product Management</strong>: Add, update, or delete products through an intuitive interface.</li>
  <li>🗂️ <strong>Category Management</strong>: Organize your catalog for better navigation.</li>
  <li>📑 <strong>Order Handling</strong>: View, process, and update customer orders.</li>
  <li>👥 <strong>User Roles</strong>: Manage users and control access levels efficiently.</li>
</ul>

<hr>

<h2>🛠️ Tech Stack</h2>
<ul>
  <li><strong>MongoDB</strong> – Flexible NoSQL database.</li>
  <li><strong>Express.js</strong> – Lightweight backend framework.</li>
  <li><strong>React.js</strong> – Dynamic frontend with responsive UI.</li>
  <li><strong>Node.js</strong> – Backend runtime environment.</li>
  <li><strong>Stripe API</strong> – Payment gateway integration.</li>
  <li><strong>JWT</strong> – Secure authentication and session management.</li>
</ul>

<hr>

<h2>📁 Folder Structure</h2>
<pre>
/
├── admin/        # React-based Admin Dashboard
├── backend/      # Node.js + Express Backend
├── frontend/     # React-based User Frontend
├── .gitignore
├── README.md
</pre>

<hr>

<h2>⚙️ Getting Started</h2>

<h3>✅ Prerequisites</h3>
<ul>
  <li>Git</li>
  <li>Node.js</li>
  <li>npm</li>
</ul>

<h3>🔽 Clone the Repository</h3>
<pre><code>git clone https://github.com/krishna1505/EKart.git</code></pre>

<h3>📦 Installation</h3>
<pre><code>
cd admin
npm install

cd ../frontend
npm install

cd ../backend
npm install
</code></pre>

<h3>🔐 Environment Variables</h3>
<p>Create <code>.env</code> files in the following directories:</p>
<ul>
  <li><code>admin/.env</code></li>
  <li><code>frontend/.env</code></li>
  <li><code>backend/.env</code></li>
</ul>

<p>Example:</p>
<pre><code>VITE_BACKEND_URL="http://localhost:4000"</code></pre>

<h3>Backend .env Sample:</h3>
<pre><code>
PORT=4000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
</code></pre>

<hr>

<h2>🚀 Running the Project</h2>

<h3>▶️ Admin Dashboard</h3>
<pre><code>
cd admin
npm run dev
</code></pre>
<p>Visit: <a href="http://localhost:5174" target="_blank">http://localhost:5174</a></p>

<h3>▶️ Backend Server</h3>
<pre><code>
cd backend
npm run server
</code></pre>
<p>API running on: <a href="http://localhost:4000" target="_blank">http://localhost:4000</a></p>

<h3>▶️ User Frontend</h3>
<pre><code>
cd frontend
npm run dev
</code></pre>
<p>Visit: <a href="http://localhost:5173" target="_blank">http://localhost:5173</a></p>

<hr>

<h2>🙌 Contribution</h2>
<p>Feel free to fork this repo and contribute via PRs. Any suggestions, bug fixes, or improvements are welcome!</p>

<hr>

<h2>📄 License</h2>
<p>This project is open-source and available under the <strong>MIT License</strong>.</p>
