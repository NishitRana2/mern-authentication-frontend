# 🔐 MERN Authentication System

A comprehensive, full-featured authentication system developed using the MERN stack, providing robust user management and security features.

## 🌟 Key Features

* 🔑 **User Registration & Login**
  - Secure authentication using JSON Web Tokens (JWT)
  - Robust user registration process

* 📧 **Email Verification**
  - One-Time Password (OTP) based email verification
  - Secure account activation mechanism

* 🔒 **Password Management**
  - Secure password reset functionality
  - Email-based recovery process

* 🛡️ **Access Control**
  - Role-based Access Control (RBAC)
  - Granular authorization management

## 🚀 Tech Stack

- **Database**: MongoDB
- **Backend**: Express.js, Node.js
- **Frontend**: React.js + vite
- **Styling**: Tailwind CSS
- **Authentication**: JWT
- **Additional Tools**:
  - Nodemailer (Email service)
  - bcrypt (Password hashing)

## 🏗️ Project Structure

### Backend
- RESTful API development
- Secure authentication endpoints
- Database interaction with MongoDB
- Token-based authorization

### Frontend
- Responsive React application with vite
- Modern UI components
- State management
- Secure authentication flows

## 🛠️ Installation

### Prerequisites
- Node.js
- npm
- MongoDB

### Setup Steps
1. **Clone the Frontend Repository**
   ```bash
   git clone https://github.com/NishitRana2/mern-authentication-frontend.git
   cd mern-authentication-frontend
   ```
   
2. **Clone the Backend Repository**
   ```bash
   git clone https://github.com/NishitRana2/mern-authentication-api.git
   cd mern-authentication-api
   ```

3. **Install Dependencies**
   ```bash
   # Install backend dependencies
   cd backend
   npm install

   # Install frontend dependencies
   cd ../frontend
   npm install
   ```

4. **Configure Environment**
   - Create `.env` files in backend and frontend
   - Add necessary configuration variables for frontend
     - VITE_BACKEND_URL
   - Add necessary configuration variables for backend
     - MONGODB_URI
     - JWT_SECRET
     - NODE_ENV
     - SMTP_USER
     - SMTP_PASS
     - SENDER_EMAIL 
     

5. **Run the Application**
   ```bash
   # Start backend
   cd backend
   npm start

   # Start frontend
   cd frontend
   npm run dev
   ```

## 🔐 Security Features

- JWT authentication
- Password encryption with bcrypt
- Secure email verification
- Protected API routes
- Input validation
- Comprehensive error handling


## 📦 Backend Repository

[View Backend Repository](https://github.com/NishitRana2/mern-authentication-api)


---

🚀 **Secure. Simple. Powerful.** Authentication Made Easy! 🔐
