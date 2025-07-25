# 🩸 LifeLink - Blood Donation Management System

**LifeLink** is a modern, responsive web application designed to streamline blood donation activities and manage emergency blood requests. It bridges the gap between donors, hospitals, and blood banks through real-time connectivity, ensuring that the right blood reaches the right place at the right time.

---

## 🚀 Features

- 🔴 **Real-Time Emergency Blood Requests**
- 🧑‍🤝‍🧑 **Donor Management & Scheduling**
- 🏥 **Blood Bank Inventory Tracking**
- 📱 **Responsive UI with Modern Animations**
- 🔔 **Real-Time Notifications via Socket.IO**
- 📊 **Interactive Dashboard for Donors, Hospitals & Blood Banks**
- 🔐 **Secure User Authentication (Flask-Login)**

---

## 🛠️ Tech Stack

| Layer       | Technology          |
|-------------|---------------------|
| Backend     | Python, Flask       |
| Frontend    | JavaScript, TailwindCSS |
| Database    | SQLAlchemy (ORM)    |
| Real-time   | Socket.IO           |
| Auth        | Flask-Login         |

---

## 📁 Project Structure

lifelink/
├── app/
│   ├── __init__.py
│   ├── models/
│   ├── routes/
│   ├── static/
│   └── templates/
├── migrations/
├── tests/
├── .env
├── .env.example
├── config.py
└── run.py


---

## ⚙️ Setup Instructions

### 1. Clone the Repository
```bash

2. Create Virtual Environment
python -m venv venv
source venv/bin/activate       # On Windows: venv\Scripts\activate

3. Install Dependencies
pip install -r requirements.txt

4. Setup Environment Variables
bash
Copy
Edit
cp .env.example .env
# Edit .env and add your configuration


5. Initialize Database
flask db init
flask db migrate
flask db upgrade


6. Run the Application
flask run


🎥 Demo Video


