# 🔌 Smart Navigation System for EV Charging 🚗⚡

A smart web application that helps electric vehicle (EV) users locate nearby charging stations, calculate optimal routes, and book available charging slots using real-time map integration and MySQL database support.

---

## 📌 Key Features

- 📍 **Find Nearby Charging Stations** using geolocation and reverse geocoding
- 🧭 **Calculate Distance** using the Haversine algorithm
- 🗺️ **Interactive Map Interface** with Leaflet.js
- 📅 **Book Charging Slots** with real-time availability tracking
- 🧾 **Store Data** using MySQL Workbench
- 🌐 **Responsive Frontend** with HTML, CSS, JavaScript
- 🐍 **Python Flask Backend** with modular app structure
- 🧬 **Database Migrations** using Alembic

---

## 🛠️ Tech Stack

| Layer        | Technologies                          |
|--------------|----------------------------------------|
| Frontend     | HTML, CSS, JavaScript, Leaflet.js      |
| Backend      | Python, Flask                          |
| Database     | MySQL Workbench (with SQLAlchemy ORM)  |
| Algorithms   | Haversine Formula, Reverse Geocoding   |

---

## 🗂️ Project Structure

Smart-Navigation-For-EV-main/

│

├── app/

│ ├── init.py # Flask app factory

│ ├── admin.py # Admin-related logic

│ ├── models.py # SQLAlchemy database models

│ ├── routes.py # Flask routes

│ ├── static/ # CSS, JS, assets

│ └── templates/ # HTML templates

│

├── migrations/ # Alembic migrations

│ ├── env.py

│ ├── script.py.mako

│ └── versions/

│

├── config.py # Database config (MySQL URI)

├── run.py # Entry point

├── README.md # Project documentation

└── requirements.txt # Dependencies

## 💡 Algorithms Used

**Haversine Formula**

Used to calculate the distance between two latitude/longitude points to find the closest charging stations.

**Reverse Geocoding**

Translates GPS coordinates into human-readable locations for better user experience.
