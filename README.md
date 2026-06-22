# 🏥 Hospital Management System

A backend-focused Hospital Management System built using FastAPI. This project is designed to manage patients, doctors, appointments, and hospital records through a REST API.

## 🚀 Features

- Patient Management
  - Add new patients
  - View patient records
  - Update patient details
  - Delete patient records

- Doctor Management
  - Register doctors
  - View doctor information
  - Update doctor details

- Appointment Management
  - Schedule appointments
  - View appointments
  - Cancel appointments

- Database Integration
  - Store and retrieve data using MongoDB

- API Documentation
  - Interactive Swagger UI provided by FastAPI

---

## 🛠️ Tech Stack

- Python
- FastAPI
- MongoDB
- Pydantic
- Uvicorn
- Git & GitHub

---

## 📂 Project Structure

```text
Hospital-Management-System/
│
├── app/
│   ├── main.py
│   ├── models/
│   ├── routes/
│   ├── database/
│   └── schemas/
│
├── requirements.txt
├── .gitignore
└── README.md
```

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/tanmaysingh00221-stack/Hospital-Management-System.git
cd Hospital-Management-System
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Virtual Environment

Linux/Mac:

```bash
source venv/bin/activate
```

Windows:

```bash
venv\Scripts\activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Server

```bash
uvicorn app.main:app --reload
```

---

## 📖 API Documentation

After starting the server:

Swagger UI:

```text
http://127.0.0.1:8000/docs
```

ReDoc:

```text
http://127.0.0.1:8000/redoc
```

---

## 🎯 Future Improvements

- JWT Authentication
- Role-Based Access Control (Admin/Doctor/Patient)
- Medical History Tracking
- Prescription Management
- Billing System
- Email Notifications
- Docker Deployment
- PostgreSQL Support

---

## 📈 Learning Outcomes

Through this project, I learned:

- REST API Development
- FastAPI Framework
- Database Integration
- API Testing
- Git & GitHub Workflow
- Backend Project Structure

---

## 👨‍💻 Author

Tanmay Singh

GitHub: https://github.com/tanmaysingh00221-stack
