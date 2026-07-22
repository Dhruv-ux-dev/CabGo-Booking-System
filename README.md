# 🚖 CabGo - Cab Booking System

A **team-developed full-stack cab booking web application** built using **Flask**, **MySQL**, **JavaScript**, and **Tailwind CSS**. The application enables users to register, book rides, manage bookings, and process payments through a modern web interface, while providing administrators with tools to manage users, drivers, cabs, and bookings.

---

## ✨ Features

### User Features
- User Registration & Login
- Browse Available Cabs
- Book Rides
- View Booking History
- Payment Management
- Responsive User Interface

### Admin Features
- Admin Dashboard
- Manage Users
- Manage Drivers
- Manage Cabs
- Manage Bookings
- Payment Monitoring

---

## 🛠️ Tech Stack

### Frontend
- HTML5
- CSS3
- JavaScript
- Tailwind CSS

### Backend
- Python
- Flask
- Flask-CORS

### Database
- MySQL

---

## 📁 Project Structure

```text
CabGo/
├── backend/
│   ├── app.py
│   ├── requirements.txt
│   └── ...
├── frontend/
│   ├── index.html
│   ├── style.css
│   ├── script.js
│   └── ...
├── Database.sql
├── README.md
└── .gitignore
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/CabGo.git
cd CabGo
```

### 2. Install Dependencies

```bash
pip install flask flask-cors mysql-connector-python
```

### 3. Configure the Database

Create a MySQL database named:

```sql
cab_booking
```

Import the provided `Database.sql` file into the database.

### 4. Configure Database Credentials

Update the MySQL configuration in `backend/app.py` (or use environment variables).

### 5. Run the Backend

```bash
python app.py
```

### 6. Launch the Frontend

Open `frontend/index.html` in your preferred web browser.

---

## 📚 Key Concepts Demonstrated

- Full-Stack Web Development
- RESTful API Development
- CRUD Operations
- User Authentication
- Database Design & Integration
- Client-Server Architecture
- Responsive Web Design

---

## 👥 Team Project

This project was developed collaboratively as part of a team. It demonstrates practical experience in full-stack web development, including frontend implementation, backend API development, database integration, and system management.

---

## 🔮 Future Enhancements

- Password Hashing
- JWT Authentication
- Google Maps Integration
- Online Payment Gateway
- Live Ride Tracking
- Email Notifications
- Docker Support
- Cloud Deployment

---

## 📄 License

This project was developed for educational purposes.
