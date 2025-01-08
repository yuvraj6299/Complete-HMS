# 🏥 Hospital Management System Backend  

A robust and scalable backend built with **Node.js**, **Express.js**, and **MongoDB** for efficiently managing hospital operations like patient records, appointments, and doctor profiles.  

---

## 🛠️ Development Responsibility  

This project was a collaborative effort:  
- The **frontend** and **dashboard** parts were developed by my team, ensuring a user-friendly interface and a powerful admin panel.  
- I was responsible for building the **backend**, which includes:  
  - Setting up the server and RESTful API endpoints.  
  - Implementing secure authentication and role-based access control.  
  - Designing and managing the MongoDB database.  
  - Developing core functionalities such as appointment management, patient records, and admin dashboard features.  
  - Deploying the backend for seamless integration with the frontend and dashboard.  

---

## ✨ Key Features  

### 🔒 **Secure Authentication**  
- **Role-Based Access Control**: Separate access for admins and patients.  
- **JWT Token Authentication**: Secure session management.  
- **Password Security**: User passwords are hashed using `bcrypt`.  

---

## 📋 Core Functionalities  

### 🔑 **For Admin**  
1. **Patient Management**: Admin can view, update, and delete patient records.  
2. **Appointment Management**: Admin can view all appointment requests, accept or reject them, and manage schedules.  
3. **Doctor Profiles**: Manage doctor details, such as specialization and availability.  
4. **Message Visibility**: Admin can view messages sent by patients on their dashboard for better communication.  
5. **Analytics Dashboard**: Admin gets a summarized view of all hospital activities, including appointments, patients, and messages.  

### 🧑‍⚕️ **For Users (Patients)**  
1. **Profile Management**: Patients can update their personal information securely.  
2. **Book Appointments**: Patients can book appointments with doctors based on availability.  
3. **Message Doctors/Admin**: Patients can send messages for queries or feedback.  

---

## 🌐 **Live Links**  

- **Frontend**: [Hospital Management Frontend](https://hospital-management-systems-yuvii.netlify.app)  
- **Backend**: [Hospital Management Backend](https://dashboard.render.com)  
- **Dashboard**: [Hospital Management Dashboard](https://admin-dashboard-hms-yuvii.netlify.app)  

---

## 🛠️ Tech Stack  

| Technology    | Purpose                              |
|---------------|--------------------------------------|
| **Node.js**   | Backend runtime environment         |
| **Express.js**| RESTful API framework               |
| **MongoDB**   | Cloud database for data management  |
| **JWT**       | Token-based authentication          |
| **bcrypt**    | Secure password hashing             |

---

## 🚀 Getting Started  

### 1️⃣ **Clone the Repository**  
```bash  
git clone https://github.com/yuvraj6299/Complete-HMS.git  
cd mernproject  

```  

### 2️⃣ **Install Dependencies**  
```bash  
npm install  
```  

### 3️⃣ **Set Up Environment Variables**  
- Create a `.env` file in the root directory.  
- Add the following environment variables:  

```plaintext  
PORT=4002

MONGO_URI=mongodb+srv://username:password@cluster0.mongodb.net/?retryWrites=true
FRONTEND_URL=http://localhost:5173

DASHBOARD_URL=http://localhost:5174

JWT_SECRET_KEY=your_jwt_secret_key
JWT_EXPIRES=7d
COOKIE_EXPIRE=7
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
CLOUDINARY_API_KEY=your_cloudinary_api_key

```  

### 4️⃣ **Run the Development Server**  
```bash  
npm run dev  
```  
- The backend server will start at `http://localhost:4002`.  

---

## 📂 Folder Structure  

```plaintext  
backend/  
├── config/          # Configuration files (database, environment variables)  
├── controllers/     # Business logic for APIs  
├── models/          # MongoDB schemas  
├── routes/          # API endpoints  
├── middlewares/     # Middleware for authentication  
├── utils/           # Utility functions  
├── .env.example     # Example environment variables  
└── server.js        # Main server entry point  
```  

---

## 🤝 Contributing  

We welcome contributions to improve the backend of this system! Here’s how you can get involved:  

1. 🍴 **Fork** the repository.  
2. 🌟 Create a **new branch** for your feature or fix.  
3. ✍️ Make your changes and **commit** them.  
4. ✅ Open a **pull request** for review.  

---

## 💬 Feedback & Support  

If you have any feedback, questions, or issues, feel free to create an issue in the repository.  

---

**Happy Coding! 🚀**  
Let’s build something impactful together!  

