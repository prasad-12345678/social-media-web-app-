# Social Media Web Application (MERN Stack)

A full-stack social media web application built using the **MERN stack** that enables users to connect, share posts, and communicate in real time.

## 🚀 Features
- User authentication and authorization using **JWT**
- User profile creation and management
- Create, like, and manage posts
- Follow and unfollow users
- Real-time chat/messaging functionality
- Responsive and modern user interface

## 🛠️ Tech Stack
**Frontend:** React, HTML, CSS, JavaScript  
**Backend:** Node.js, Express.js  
**Database:** MongoDB  
**Authentication:** JSON Web Tokens (JWT)  
**Real-Time Communication:** WebSockets  

## 📂 Project Structure
/client -> React frontend
/server -> Node.js & Express backend
/models -> MongoDB schemas
/routes -> API routes
/controllers-> Business logic

bash
Copy code

## ⚙️ Installation & Setup

1. Clone the repository  
```bash
git clone https://github.com/your-username/your-repo-name.git
Install backend dependencies

bash
Copy code
cd server
npm install
Install frontend dependencies

bash
Copy code
cd ../client
npm install
Create a .env file in the server directory and add:

env
Copy code
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
Run the application

bash
Copy code
# Run backend
npm start

# Run frontend
npm run dev
✅ Future Improvements
Add image upload support

Implement notifications

Enhance UI with animations

Improve performance and scalability

👨‍💻 Author
Lakshmi Prasad
Built as a full-stack project to demonstrate real-world MERN development skills.
