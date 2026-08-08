# 🚌 Route Hive

### Smart University Transportation Management System

Route Hive is a smart transportation management system developed to digitalize and simplify university bus management. It provides a centralized platform for managing students, drivers, buses, routes, and transportation enrollment.

The system provides role-based access for **Administrators, Users, and Drivers**. Administrators can manage buses, assign drivers, and approve or reject transportation requests. Users can register for transportation, manage their profiles, select pickup locations, and view bus information. Drivers have a dedicated interface for managing their profiles and assigned routes.

Route Hive also supports bus location tracking and real-time bus location updates, helping users access transportation information more conveniently and improving the overall transparency and efficiency of university transportation management.
## ✨ Features

- 👤 User Registration and Login
- 🔐 Role-Based Access Control
- 🚌 Bus Management
- 👨‍✈️ Driver Management
- 📝 Transportation Enrollment
- ✅ Accept / Reject Transportation Requests
- 📍 Bus Route and Transportation Management
  - 👤 User Profile Management
- 👨‍✈️ Dedicated Driver Profile
- 🛠️ Admin Dashboard
- 📊 Transportation Request Management
- 💻 Interactive Web-Based Interface
- ⚡ Fast and Efficient Backend API
## 🛠️ Technologies Used

- ⚛️ React.js — Frontend development
- 🐍 Python — Backend development
- 🔥 Flask — Backend API and server
- 🗄️ SQLite — Database management
- 🔗 SQLAlchemy — Database ORM
- 🔐 Bcrypt — Password hashing and security
- 🗺️ Map Integration — Bus route and location features
- 🌐 REST API — Frontend and backend communication
- 📦 Git & GitHub — Version control and project management

  # 🏗️ System Architecture

Route Hive follows a client-server architecture consisting of a React-based frontend, a Flask backend, and a database layer.

```text
┌──────────────────────────────┐
│        Client Layer          │
│       React Frontend         │
│                              │
│  User Dashboard              │
│  Admin Dashboard             │
│  Driver Profile              │
│  Bus Simulation              │
└──────────────┬───────────────┘
               ↓
┌──────────────────────────────┐
│      Application Layer       │
│        Flask Backend         │
│                              │
│  Authentication              │
│  User Management             │
│  Bus Management              │
│  Driver Management           │
│  Enrollment Management       │
│  Request Management          │
└──────────────┬───────────────┘
               ↓
┌──────────────────────────────┐
│         Data Layer           │
│        SQLite Database       │
│                              │
│  User Data                   │
│  Driver Data                 │
│  Bus Data                    │
│  Enrollment Data              │
│  Request Data                │
└──────────────────────────────┘

# 🚀 Installation & Setup


---

## 1. Clone the Repository

```bash
git clone <https://github.com/Basantakhanal/Route-Hive.git>
cd Sentinel-AI
```

---

# 2. Backend Setup

Navigate to the backend:

```powershell
cd backend
```

Create a Python virtual environment:

```powershell
python -m venv venv
```

Activate the virtual environment:

```powershell
.\venv\Scripts\Activate.ps1
```

Upgrade pip:

```powershell
python -m pip install --upgrade pip
```

Install all backend dependencies:

```powershell
pip install -r requirements.txt
```

---


# 4. Start the Backend

From the `backend` directory, run:

```powershell
python app.py
```


# 5. Frontend Setup

Open a **new terminal** while keeping the backend running.

Navigate to the frontend:

```powershell
cd frontend
```

Install frontend dependencies:

```powershell
npm install
```

Start the development server:

```powershell
npm run dev
```


# ▶️ Running the Complete Project

Both the backend and frontend must be running at the same time.

### Terminal 1 — Backend

```powershell
cd Route-Hive\backend
.\venv\Scripts\Activate.ps1
python app.py
```

### Terminal 2 — Frontend

```powershell
cd Route-Hive\frontend
npm install
npm run dev
```
