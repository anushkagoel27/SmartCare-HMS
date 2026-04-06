# 🏥 Smart Care HMS (Hospital Management System)

Smart Care HMS is a web-based Hospital Management System developed to improve hospital workflow with a **special focus on emergency management and home assistance services**.  
Unlike traditional hospital systems that mainly handle appointments and billing, Smart Care HMS prioritizes **critical patient care, faster response time, and better coordination between patients, doctors, and hospitals**.

---

## 🚀 Key Features

### 👤 Patient Module

- Patient registration and secure login
- View available doctors and departments
- Book and manage appointments
- Emergency case priority handling
- Request medical help using **Home Assistance**

### 👨‍⚕️ Doctor Module

- Doctor authentication
- View assigned patients
- Update patient diagnosis and treatment status
- Manage daily appointments

### 🏥 Admin Module

- Manage doctors, patients, and appointments
- Monitor emergency cases
- System-level control and hospital operations

### 🏠 Home Assistance (Highlighted Feature)

- Allows patients to request medical assistance from home
- Beneficial for elderly, disabled, or critical patients
- Reduces hospital crowding
- Enables faster medical response and remote support

---

## 🛠️ Tech Stack

**Frontend**

- HTML
- CSS
- JavaScript
- Bootstrap

**Backend**

- Django (Python)

**Database**

- SQLite (Django default)

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
https://github.com/anushkagoel27/SmartCare-HMS.git

```

### 2️⃣ Navigate to Project Directory
```bash
cd SmartCare-HMS
```

### 3️⃣ Create and Activate Virtual Environment (Recommended)
```bash
python -m venv venv
venv\Scripts\activate
```


### 4️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```


### 5️⃣ Apply Database Migrations
```bash
python manage.py makemigrations
python manage.py migrate
```


### 6️⃣ Run the Development Server
```bash
python manage.py runserver
```


### 7️⃣ Open in Browser
```bash
http://127.0.0.1:8000/
```
