# 🍽️ DjibReco
### *AI-powered restaurant & café recommender for Djibouti*

[![Status](https://img.shields.io/badge/Status-In_Development-yellow?style=flat-square)](.)
[![Stack](https://img.shields.io/badge/Stack-Python_%7C_Flask_%7C_Scikit--learn-blue?style=flat-square)](.)
[![Domain](https://img.shields.io/badge/Domain-AI_%7C_Recommendation_Systems-purple?style=flat-square)](.)
[![License](https://img.shields.io/badge/License-MIT-lightgrey?style=flat-square)](.)

> How can users in Djibouti quickly find cafés and restaurants that match their tastes and budget?  
> **DjibReco** answers that question with a hybrid AI recommendation engine.

---

## 🎯 Overview

**DjibReco** is an AI-powered web application that recommends cafés and restaurants in Djibouti by combining two recommendation approaches into a single hybrid model — delivering personalized suggestions based on user preferences, ratings, and budget.

---

## 🤖 Recommendation System

```
📋 Content-Based          👥 Collaborative           🔀 Hybrid Model
─────────────────         ──────────────────         ──────────────────
Cuisine type              User ratings               Weighted combination
Price range               Similar users              of both approaches
Tags & location           Behavioral patterns        Reduces cold-start
```

---

## 🚀 Features

| Feature | Status |
|:---|:---|
| User authentication (register / login) | 🔄 Planned |
| Add and rate restaurants | 🔄 Planned |
| Personalized recommendations | 🔄 Planned |
| Hybrid recommendation engine | 🔄 Planned |
| Admin dashboard | 🔄 Planned |
| Budget-based filtering | 🔄 Planned |
| Restaurant search and filtering | 🔄 Planned |

---

## 🛠️ Tech Stack

```
Backend      →  Python 3 · Flask · SQLAlchemy · Scikit-learn
Database     →  SQLite (development) · PostgreSQL (production)
Frontend     →  HTML · CSS · Jinja2 templates
Data         →  Local CSV dataset · User ratings
```

---

## 📁 Project Structure

```
DjibReco/
├── app/
│   ├── __init__.py
│   ├── routes.py
│   ├── models.py
│   ├── recommender.py
│   ├── templates/
│   └── static/
├── data/
│   └── restaurants.csv
├── tests/
├── config.py
├── run.py
└── requirements.txt
```

---

## ⚡ Installation & Launch

### 1. Clone the repository
```bash
git clone https://github.com/fatouu50/DjibReco.git
cd DjibReco
```

### 2. Create and activate a virtual environment
```bash
# Windows
python -m venv venv
.\venv\Scripts\activate

# macOS / Linux
python3 -m venv venv
source venv/bin/activate
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the application
```bash
python run.py
```

The app will be available at **`http://localhost:5000`**

---

## 🔮 Future Improvements

- 🌍 Online deployment
- 📍 Geolocation-based filtering
- 📊 Improved ranking algorithm
- 👥 Real user dataset integration
- 💬 Reviews and sentiment analysis

---
