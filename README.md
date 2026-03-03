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

## 🤝 Comment Contribuer et Fusionner

Chaque fonctionnalité est développée dans une branche dédiée :

| Branche | Développeur |
|:---|:---|
| `fatouma` | Fatouma |
| `madina` | Madina |
| `mako` | Mako |
| `kadiga` | Kadiga |
| `samira` | Samira |
| `asma` | Asma |
| `abdoulrazack` | Abdoulrazack |
| `kenedid` | Kenedid |

> ⚠️ **Règle absolue :** Aucun développement direct sur `main`. La branche `main` doit toujours rester stable et fonctionnelle.

---

### Étape 1 — Travailler sur sa branche

Commence toujours par te placer sur ta branche :

```bash
git checkout fatouma
```

> Remplace `fatouma` par le nom de ta propre branche.

---

### Étape 2 — Enregistrer et envoyer son travail

Une fois ta fonctionnalité terminée :

```bash
git add .
git commit -m "Description claire de ce que tu as fait"
git push origin fatouma
```

Exemple pour une autre branche :

```bash
git checkout madina
git add .
git commit -m "Implémentation de la base de données terminée"
git push origin madina
```

---

### Étape 3 — Fusionner dans `main` après validation

Une fois la fonctionnalité testée et validée, fusionner dans `main` :

```bash
# 1. Revenir sur main
git checkout main

# 2. Récupérer les dernières mises à jour
git pull origin main

# 3. Fusionner ta branche
git merge fatouma

# 4. Envoyer sur GitHub
git push origin main
```

Répéter le même processus pour chaque branche :

```bash
git merge madina
git merge mako
git merge kadiga
git merge samira
git merge asma
git merge abdoulrazack
git merge kenedid
```

---

### 📋 Résumé du flux de travail

```
Ta branche (ex: fatouma)
        │
        │  git add . && git commit && git push
        │
        ▼
  Branche distante (GitHub)
        │
        │  Tests validés ✅
        │
        ▼
      main  ←  git merge fatouma
```

