# MediSync - Hospital Management System

## Description
**MediSync** is a comprehensive Hospital Management System built on the MERN stack to enhance hospital operations. This system includes features such as secure user authentication, efficient appointment scheduling, patient record management, and real-time communication between doctors and patients. It provides a scalable and user-friendly platform to streamline healthcare workflows and improve the hospital experience.

## Features
- **User Authentication**: Secure login for patients, doctors, and administrators.
- **Appointment Scheduling**: Easy booking, rescheduling, and cancellation of appointments.
- **Patient Records Management**: Store, access, and update patient health records.
- **Doctor-Patient Communication**: Real-time messaging for consultations and follow-ups.
- **Admin Dashboard**: Manage users, appointments, and view analytics.
- **Secure Data Storage**: Ensure patient privacy and data security with MongoDB.

## Tech Stack
- **Frontend**: React.js
- **Backend**: Node.js and Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **State Management**: Redux (optional)

## Getting Started
Follow these instructions to set up the project locally.

### Prerequisites
- Node.js installed
- MongoDB installed or access to a MongoDB cloud instance
- Git installed

### Installation
1. **Clone the repository**
   ```bash
   git clone ~link here~
   cd MediSync
   ```

## Install dependencies

1. **Install admin dependencies**
   ```bash
   cd admin
   npm install
   ```

2. **Install frontend dependencies**
   ```bash
   cd frontend
   npm install
   ```

3. **Install backend dependencies**
   ```bash
   cd backend
   npm install
   ```

4. **Set up environment variables**
   In the backend directory, create a `.env` file with the following:

   ```env
   MONGODB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   CLOUDINARY_NAME=your_cloudinary_name
   CLOUDINARY_API_KEY=your_cloudinary_api_key
   CLOUDINARY_SECRET_KEY=your_cloudinary_secret_key
   ADMIN_EMAIL=your_admin_email
   ADMIN_PASSWORD=your_admin_password
   STRIPE_SECRET_KEY=your_stripe_secret_key
   RAZORPAY_KEY_ID=your_razorpay_key_id
   RAZORPAY_KEY_SECRET=your_razorpay_key_secret
   CURRENCY=INR
   ```

   The frontend and admin `.env` files should point to `http://localhost:4000`.

   Run the application

5. **Start server:**
   ```bash
   cd backend
   npm run server
   ```

6. **Start Admin Panel:**
   ```bash
   cd admin
   npm run dev
   ```

7. **Start Frontend Panel:**
   ```bash
   cd frontend
   npm run dev
   ```

# Topics
Hospital Management, MERN Stack, MongoDB, Express.js, React, Node.js, Healthcare App, Patient Records, Appointments.

# Contact
For any questions or feedback, please contact [Hiral dhar](https://www.linkedin.com/in/hiral-dhar-1079aa282)