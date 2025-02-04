# MERN-Stack-Expense-Tracker-Application

📌 Overview
Expense Tracker is a full-stack MERN application that helps users track their income and expenses efficiently. It provides authentication, real-time expense analysis, and interactive dashboards for financial management.

![Screenshot 2025-02-04 161429](https://github.com/user-attachments/assets/6a0294f4-6d70-4627-b34e-597db89940fb)



🚀 Features
✅ User Authentication (Login, Signup, JWT authentication)
✅ Add, Edit & Delete Transactions (Income & Expenses)
✅ Real-time Expense Chart & Analytics
✅ Filter Transactions by Date, Category, or Type
✅ Secure Backend with MongoDB & Express
✅ Fully Responsive UI (Material UI / Tailwind CSS)
✅ Dark Mode Support (Optional)

🛠️ Tech Stack
Frontend (React)
React.js – Component-based UI
Redux Toolkit – State management
Axios – HTTP requests to the backend
Material UI / Tailwind CSS – Styling & UI components
Chart.js / Recharts – Visual representation of transactions
Backend (Node.js & Express.js)
Node.js – JavaScript runtime
Express.js – API development
MongoDB – NoSQL database
Mongoose – ODM for MongoDB
JWT Authentication – Secure authentication system
📦 Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/mern-expense-tracker.git
cd mern-expense-tracker
2️⃣ Install Dependencies
Backend (Node.js + Express)
cd backend
npm install
Frontend (React)
cd frontend
npm install
🔧 Configuration
Create a .env file in the backend/ directory and add the following:

MONGO_URI=mongodb+srv://your-username:your-password@cluster.mongodb.net/expenseDB
JWT_SECRET=your-secret-key
PORT=5000
Replace with your MongoDB connection string and JWT secret key.

🚀 Running the Application
Start Backend Server
cd backend
npm start
Start Frontend
cd frontend
npm start
📌 The frontend will run on http://localhost:3000
📌 The backend will run on http://localhost:5000

📜 Project Structure
mern-expense-tracker/
│── backend/             # Node.js + Express.js Server
│   ├── models/          # Mongoose Models
│   ├── routes/          # Express Routes
│   ├── controllers/     # Business Logic
│   ├── middleware/      # Authentication Middleware
│   ├── config/          # Database Configuration
│   ├── .env             # Environment Variables
│   ├── server.js        # Main Backend Entry Point
│── frontend/            # React.js Frontend
│   ├── src/
│   │   ├── components/  # Reusable Components
│   │   ├── pages/       # Page-Level Components
│   │   ├── store/       # Redux Store
│   │   ├── App.js       # Main App Component
│   │   ├── index.js     # React Entry Point
│   ├── package.json     # Frontend Dependencies
│── README.md            # Documentation
│── .gitignore           # Git Ignore File
🔑 API Endpoints
Method	Endpoint	Description
POST	/api/auth/register	Register a new user
POST	/api/auth/login	User login & get token
GET	/api/transactions	Fetch all transactions
POST	/api/transactions	Add a new transaction
PUT	/api/transactions/:id	Update a transaction
DELETE	/api/transactions/:id	Delete a transaction
📝 To-Do List
 Add user authentication
 Implement CRUD operations for transactions
 Add category-based filtering
 Integrate Google OAuth login
 Implement Recurring Expense Reminders
 Deploy on Vercel (Frontend) & Render (Backend)
🙌 Contribution
Want to contribute? Follow these steps:

Fork the repository.
Create a new branch (feature-branch).
Commit your changes: git commit -m "Added a new feature"
Push the changes: git push origin feature-branch
Open a Pull Request.
🔒 Limitations
No Multi-Currency Support – Only supports a single currency.
No AI Integration – Does not provide automated insights.
Limited Reporting – Lacks advanced financial reports.
📜 License
This project is open-source under the MIT License.

💬 Contact
📧 Email: your.email@example.com
🔗 LinkedIn: Your LinkedIn
💻 GitHub: Your GitHub
