# 🍽️ DjibReco
### *Recommandation de cafés et restaurants à Djibouti propulsée par l'IA*

[![Statut](https://img.shields.io/badge/Statut-En_Développement-yellow?style=flat-square)](.)
[![Stack](https://img.shields.io/badge/Stack-Python_%7C_Flask_%7C_Scikit--learn-blue?style=flat-square)](.)
[![Domaine](https://img.shields.io/badge/Domaine-IA_%7C_Systèmes_de_Recommandation-purple?style=flat-square)](.)
[![Licence](https://img.shields.io/badge/Licence-MIT-lightgrey?style=flat-square)](.)

> Comment trouver rapidement à Djibouti un café ou un restaurant qui correspond à ses goûts et à son budget ?
> **DjibReco** répond à cette question grâce à un moteur de recommandation hybride basé sur l'IA.

---

## 🎯 Présentation

**DjibReco** est une application web intelligente qui recommande des cafés et restaurants à Djibouti en combinant deux approches de recommandation dans un modèle hybride — offrant des suggestions personnalisées selon les préférences, les notes et le budget de chaque utilisateur.

---

## 🤖 Système de Recommandation

```
📋 Filtrage par Contenu     👥 Filtrage Collaboratif
──────────────────────      ────────────────────────
Type de cuisine             Notes des utilisateurs
Gamme de prix               Utilisateurs similaires
Tags & localisation         Comportements
```

---

## 🚀 Fonctionnalités

| Fonctionnalité | Statut |
|:---|:---|
| Authentification (inscription / connexion) | 🔄 Prévu |
| Ajout et notation de restaurants | 🔄 Prévu |
| Recommandations personnalisées | 🔄 Prévu |
| Tableau de bord administrateur | 🔄 Prévu |
| Filtrage par budget | 🔄 Prévu |
| Recherche et filtrage de restaurants | 🔄 Prévu |

---

## 🛠️ Stack Technique

```
Backend      →  Python 3 · Flask · SQLAlchemy · Scikit-learn
Base données →  SQLite (développement) · PostgreSQL (production)
Frontend     →  HTML · CSS · Templates Jinja2
Données      →  Fichier CSV local · Notes utilisateurs
```

---

## 📁 Structure du Projet

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

## ⚡ Installation & Lancement

### 1. Cloner le dépôt
```bash
git clone https://github.com/fatouu50/DjibReco.git
cd DjibReco
```

### 2. Créer et activer un environnement virtuel
```bash
# Windows
python -m venv venv
.\venv\Scripts\activate

# macOS / Linux
python3 -m venv venv
source venv/bin/activate
```

### 3. Installer les dépendances
```bash
pip install -r requirements.txt
```

### 4. Lancer l'application
```bash
python run.py
```

L'application sera disponible sur **`http://localhost:5000`**

---

## 🔮 Améliorations Futures

- 🌍 Déploiement en ligne
- 📍 Filtrage par géolocalisation
- 📊 Amélioration de l'algorithme de classement
- 👥 Intégration d'un vrai jeu de données utilisateurs
- 💬 Analyse des avis et des sentiments

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

Une fois la fonctionnalité testée et validée :

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

### 📋 Résumé du Flux de Travail

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

---
